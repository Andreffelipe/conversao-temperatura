FROM node:19-alpine

WORKDIR /app/api

COPY package*.json /app/api/

RUN npm install

COPY . .

EXPOSE 8080

CMD [ "node" ,"server.js"]