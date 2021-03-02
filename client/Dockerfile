FROM node:lts
WORKDIR /app
COPY .npmrc ./
COPY package*.json ./
RUN npm ci
COPY ./ ./
EXPOSE 80
CMD [ "npm", "start"]
