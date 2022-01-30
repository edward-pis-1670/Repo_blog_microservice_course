From node:alpine

ENV CI=true

Workdir /app

Copy package.json ./

Run npm install

Copy ./ ./

CMD npm start
