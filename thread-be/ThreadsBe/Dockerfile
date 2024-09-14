FROM node:20
WORKDIR /app
COPY package*.json ./
RUN npm install
RUN npm install nodemon
RUN npm install amqplib
COPY . .
EXPOSE 5000
CMD ["npm", "start"]
