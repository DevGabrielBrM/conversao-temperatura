FROM node:22.6.0
WORKDIR /spp
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]