FROM node:alpine

WORKDIR /usr/app

COPY packages*.json ./

RUN npm install

EXPOSE 3000

CMD npm start
