FROM node:19.5.0
LABEL devops-elite.version="1.0"
LABEL maintainer="Jarbson Santana de Jesus"
LABEL devops-elite.release-date="2023-01-24"
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "node", "server.js" ]