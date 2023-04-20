FROM node:19-alpine3.16

COPY . /app

WORKDIR /app

RUN npm ci

EXPOSE 8080

CMD ["npm", "run", "dev"]