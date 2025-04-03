# Dockerfile for the client
# Build stage
FROM node:20.14.0 AS build
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
CMD [ "npm" , "run" , "build" ]