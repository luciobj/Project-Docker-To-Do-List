FROM node:lts AS build
WORKDIR /todo-app/back-end
COPY package*.json ./
RUN npm install
COPY . .
RUN npm start
RUN npm run build