FROM node:16

WORKDIR /client

ADD . /client

RUN yarn install

RUN yarn global add @quasar/cli

COPY package*.json ./client

COPY . /client

CMD ["yarn", "quasar", "dev"]
