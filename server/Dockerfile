FROM node:alpine

WORKDIR /nodejs-docker-aws-ecs

COPY package.json .

RUN npm install

COPY . .

EXPOSE 5000

CMD [ "node", "app.js" ]