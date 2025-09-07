FROM node:18-alpine

WORKDIR /app

# Copia só os manifests primeiro
COPY package*.json ./

RUN npm install

# Agora copia o resto do código
COPY . .

EXPOSE 3000

CMD ["npm", "start"]
