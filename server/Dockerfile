FROM node:18-alpine3.20

WORKDIR /app
COPY package*.json ./

RUN npm ci --force

COPY . .

EXPOSE 5000
CMD ["node", "./index.js"]