FROM node:12.7.0

WORKDIR /usr/src/app

COPY . .

RUN npm install
RUN npm install bcrypt
EXPOSE 8080

CMD [ "npm", "run", "dev" ]