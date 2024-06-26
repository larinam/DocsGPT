FROM node:20.15-bullseye-slim


WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .

EXPOSE 5173

CMD [ "npm", "run", "dev", "--" , "--host"]
