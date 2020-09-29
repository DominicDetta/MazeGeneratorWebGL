FROM node:10

WORKDIR /home/node/app

RUN npm install -g live-server

EXPOSE 8080

CMD ["live-server","./public/index.html","--host 0.0.0.0","--port 8080"]