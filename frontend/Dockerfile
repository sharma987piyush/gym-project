FROM node

WORKDIR /app

COPY package.json package-lock.json ./

RUN npm install

COPY . .

RUN npm install react-spinner react-toastify react-router-dom axios

CMD ["npm", "run", "dev"]
