FROM node:current-slim

WORKDIR /usr/src/app
COPY server/. .
RUN npm install

EXPOSE 3000
CMD [ "npm", "start" ]
