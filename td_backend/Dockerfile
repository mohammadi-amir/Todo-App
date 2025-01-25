FROM node:14

WORKDIR /app

RUN npm install nodemon -g

COPY package.json .

RUN npm install

COPY . .
# wenn die Container ausgeführt wird
CMD [ "npx", "nodemon", "app.js" ]
