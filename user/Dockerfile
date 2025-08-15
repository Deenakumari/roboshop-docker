FROM node:20
WOPRKDIR /opt/server
COPY * js .
Copy package.json .
RUN npm install
ENV MONGO=true \
    REDIS_URL='redis://redis:6379' \
    MONGO_URL="mongodb://mongodb:27017/users"
CMD ["node", "server.js"]    