FROM node:14
WORKDIR /frontendapp
COPY package*.json ./
RUN npm install
ADD . .
EXPOSE 3000
CMD ["npm", "start"]
