FROM node:14

WORKDIR /myapp

RUN npm i pg
RUN npm i express
RUN npm install

COPY . .

CMD ["node", "backendApp.js"]