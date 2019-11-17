FROM node:10

WORKDIR /server/


COPY package*.json ./

RUN npm install

# Bundle app source
COPY . /server/

EXPOSE 3000
CMD [ "node", "server.js" ]