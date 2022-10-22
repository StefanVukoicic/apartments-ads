FROM node:current-alpine3.16

WORKDIR /apartments-ads

COPY package*.json /apartments-ads/

RUN npm install

COPY . /apartments-ads/

EXPOSE 3000

CMD ["npm", "start"]