#specify a base image
FROM node:alpine

WORKDIR /usr/app

COPY ./package.json ./package.json
RUN npm install
COPY ./ ./

CMD ["npm", "start"]

