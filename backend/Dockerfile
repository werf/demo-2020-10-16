FROM node:14-stretch
RUN apt update && apt install -y tzdata locales
ADD / /app
WORKDIR /app
RUN npm ci
