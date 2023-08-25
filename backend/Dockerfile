FROM node
COPY package.json .
COPY package-lock.json .
RUN npm install
COPY server.js .
COPY usuarios.json .
COPY database.json .
EXPOSE 8000
CMD [ "npm", "start" ]
