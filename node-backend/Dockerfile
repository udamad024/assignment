FROM node:14-alpine
WORKDIR /app
COPY . .
RUN npm install
ENV MONGO_URI=mongodb://mongo-service:27017/mydatabase
EXPOSE 3000
CMD ["node", "server.js"]