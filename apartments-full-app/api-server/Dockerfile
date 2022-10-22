FROM node:current-alpine3.16

WORKDIR /api-server

COPY package*.json /api-server/

RUN npm install

COPY . /api-server/

EXPOSE 8080

CMD ["npm", "start"]