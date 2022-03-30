FROM node:12.22.10

WORKDIR /app

COPY package*.json /app/

RUN npm install --only=prod

COPY src /app/src

CMD cd /app && npm run start