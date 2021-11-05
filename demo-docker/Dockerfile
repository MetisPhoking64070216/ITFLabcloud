FROM node:12.21.0-alpine3.12

WORKDIR /usr/src/app

COPY public /usr/share/nginx/html

RUN npm install

EXPOSE 8000

CMD [ "node", "main.js" ]
