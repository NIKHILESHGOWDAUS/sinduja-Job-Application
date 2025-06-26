FROM node:18

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

# Ensure uploads folder exists
RUN mkdir -p /app/uploads

EXPOSE 3604

CMD ["node", "server.js"]

