FROM node:lts AS build
WORKDIR /todo-app/tests
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build