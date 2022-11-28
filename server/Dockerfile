FROM node:16
WORKDIR /streamserver

COPY . .

RUN npm install package.json 
EXPOSE 8080
ENV MONGO_CONNECTION_URL=mongodb://elgenesis:block@streamdb:27017

CMD ["node","/streamserver/servegridfs.js"]
