FROM node:current-alpine3.16

WORKDIR /Scraper

COPY package*.json /Scraper/

RUN npm install

COPY . /Scraper/

CMD ["npm", "run", "dev"]