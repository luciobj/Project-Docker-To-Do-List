FROM node:alpine AS build
WORKDIR /app
COPY . .
ADD ./node_modules.tar.gz ./
ENTRYPOINT ["npm", "test"]
