FROM node:18.13.0-alpine AS build-env

WORKDIR /app
# replace with your projects name
COPY ./package*.json ./
RUN npm install
RUN ls
COPY ./ ./


ENV PORT=3000
EXPOSE 3000


CMD [ "npm", "start" ]