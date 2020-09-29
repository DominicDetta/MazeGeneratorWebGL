FROM node:10

USER node
WORKDIR /home/node/app

RUN npm install -g live-server

EXPOSE 8080

CMD ["live-server --host 0.0.0.0 --port 8080 /home/node/app"]