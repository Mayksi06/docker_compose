FROM node:lts-alpine3.15

WORKDIR /home/node/app

COPY *.js /home/node/app/

COPY *.json /home/node/app/

RUN npm install

CMD node index.js

EXPOSE 3000
