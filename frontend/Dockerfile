FROM node:20.14-bullseye-slim


WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .

EXPOSE 5173

CMD [ "npm", "run", "dev", "--" , "--host"]
