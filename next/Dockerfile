FROM node:latest

WORKDIR /usr/src/next

COPY ./ /usr/src/next

RUN npm install

COPY ./ /usr/src/next

RUN npm run build

CMD [ "npm" , "start"]
