FROM node:20.9-slim as installer

USER node
WORKDIR /usr/src/app

ENV YARN_VERSION=4.0.2
RUN yarn policies set-version $YARN_VERSION

COPY package.json yarn.lock ./

CMD ["yarn", "install", "--immutable"]
