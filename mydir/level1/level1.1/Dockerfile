FROM node:current-slim

WORKDIR /usr/src/app
COPY level1.2/. .

RUN pwd

RUN ls -la

RUN npm install

RUN echo hi this is a test 5

EXPOSE 3000
CMD [ "npm", "start" ]
