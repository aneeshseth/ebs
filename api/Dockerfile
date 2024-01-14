FROM node:16

WORKDIR /usr/src/app

COPY . .

RUN npm install
RUN npm install typescript
RUN npm run build

CMD ["npm", "run", "start"]

EXPOSE 3004