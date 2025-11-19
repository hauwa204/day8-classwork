FROM node:18-alpine

WORKDIR /app

COPY package.json .

RUN np install

COPY . .

EXPOSE 3000

CMD {"node", "server.js"}
