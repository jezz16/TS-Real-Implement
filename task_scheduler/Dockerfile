FROM node:18
       WORKDIR /task_scheduler
       COPY package*.json ./
       RUN npm install
       RUN npm install lodash
       COPY . .
       CMD ["node", "index.js", "indexMOICS.js"]
