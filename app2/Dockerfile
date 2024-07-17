FROM node:latest
WORKDIR /app

COPY . .

RUN npm install

EXPOSE 4001

ENTRYPOINT ["node", "index.js"]