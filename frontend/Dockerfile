FROM node:12
WORKDIR /app
ADD . /app
COPY package*.json ./
RUN npm install
COPY . .
CMD npm start
