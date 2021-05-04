FROM node:10

RUN mkdir /client

WORKDIR /client

ADD . /client

RUN yarn install

RUN yarn global add @quasar/cli

COPY package*.json ./client

COPY . /client/

EXPOSE 8000