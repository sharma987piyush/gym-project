FROM node

WORKDIR /app

COPY package.json package-lock.json ./  

RUN npm i express cors dotenv

COPY . .  

CMD ["npm", "run", "dev"]
