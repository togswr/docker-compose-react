FROM node:14.15.4-slim

WORKDIR /app

ENV PATH /app/node_modules/.bin:$PATH

COPY ./app/package.json ./
RUN npm install --silent
RUN npm install react-scripts -g --silent

COPY ./app ./

CMD ["npm", "start"]
