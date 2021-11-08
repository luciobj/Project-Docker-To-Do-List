FROM node:lts AS build
WORKDIR /todo-app/front-end
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build