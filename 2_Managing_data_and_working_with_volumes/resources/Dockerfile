FROM node:14

ARG DEF_PORT=80

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV PORT $DEF_PORT

EXPOSE $PORT 

CMD [ "npm", "start" ]