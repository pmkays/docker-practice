FROM node:14-alpine

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

EXPOSE 80

ENV MONGODB_USERNAME=paula
ENV MONGODB_PASSWORD=secret

CMD ["npm", "start"]