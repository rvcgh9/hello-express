FROM node:20.9-slim

ENV YARN_VERSION=4.0.2

USER node
WORKDIR /usr/src/app

RUN yarn policies set-version $YARN_VERSION
