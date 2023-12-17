FROM node:8

WORKDIR /app

COPY package.json .
RUN npm install

COPY node.js .

ENTRYPOINT ["node","node.js"]
