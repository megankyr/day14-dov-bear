FROM node:20

WORKDIR /app

COPY main.js .
COPY package.json .
COPY package-lock.json .
COPY public public
COPY views views

RUN npm ci

ENV PORT=3000 INSTANCE_NAME="dov-bear"
EXPOSE ${PORT}
ENTRYPOINT node main.js