FROM node:10
WORKDIR usr/src/app
COPY package*.json ./
RUN npm install
copy . .
CMD node src/app.js
