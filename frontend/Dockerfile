FROM node:20-alpine
WORKDIR /opt/server
COPY package*.json .
COPY *js .
RUN npm install
ENV DB_HOST="mysql"
CMD ["node","server.js"]