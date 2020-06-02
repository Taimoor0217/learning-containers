FROM node:current-slim

WORKDIR /app
COPY package.json .
RUN npm install

ENV PATH /app/node_modules/.bin:$PATH

EXPOSE 3000
CMD [ "npm", "start" ]

COPY . .