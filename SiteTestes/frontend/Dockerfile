FROM node:18.14.2-alpine3.17

WORKDIR /usr/app

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 4000

CMD [ "npm", "run", "dev" ]