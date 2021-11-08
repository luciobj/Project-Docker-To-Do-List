FROM node:alpine AS build
WORKDIR /app
EXPOSE 3000
COPY . .
ADD ./node_modules.tar.gz ./
ENTRYPOINT ["npm", "start"]
