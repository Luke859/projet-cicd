FROM node:16-alpine

WORKDIR /order_app

# install dependencies
COPY package*.json ./

RUN npm install

COPY . ./

EXPOSE 3002

CMD ["npm", "run", "start"]