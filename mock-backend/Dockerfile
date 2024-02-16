FROM node:20.11.0-bullseye-slim


WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .

EXPOSE 7091

CMD [ "npm", "run", "start"]
