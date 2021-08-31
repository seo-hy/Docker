FROM node:14
LABEL email = "seok02h@khu.ac.kr"
LABEL name = "seohyun"

WORKDIR /usr/src/app

COPY package*.json ./
COPY . .

RUN npm install

EXPOSE 8000
CMD [ "node", "server.js" ]