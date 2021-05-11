FROM node:14
WORKDIR /app
RUN npm install express
RUN npm install mysql
COPY . /app
EXPOSE 3000
CMD ["node","server.js"]
