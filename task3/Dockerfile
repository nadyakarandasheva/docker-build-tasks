
FROM node:16-alpine

WORKDIR /home/ilovedocker/app

COPY packages/package*.json ./

RUN npm install

COPY src/ ./

EXPOSE 3032

ENTRYPOINT ["node", "main.js"]
