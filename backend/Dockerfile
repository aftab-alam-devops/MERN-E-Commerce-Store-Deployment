FROM node:18
WORKDIR /app
COPY package*.json ./
RUN npm install

COPY backend/ .

EXPOSE 5000

CMD ["npm", "start"]