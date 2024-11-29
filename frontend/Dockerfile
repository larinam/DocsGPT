FROM node:20.12.2-bullseye-slim


WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .

EXPOSE 5173

CMD [ "npm", "run", "dev", "--" , "--host"]
