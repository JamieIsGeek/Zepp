FROM node:18
USER node

COPY --chown=node:node . /zeppelin

WORKDIR /zeppelin/backend
RUN npm ci && && npm i ts-toolbelt && npm run build
