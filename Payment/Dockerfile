FROM node:18

WORKDIR /usr/app

COPY package*.json ./

RUN yarn && yarn add typescript@4.5.2

RUN yarn build

COPY . ./

CMD ["yarn", "start"]
