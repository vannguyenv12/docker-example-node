FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=van
ENV MONGODB_PASSWORD=nguyen

CMD [ "npm", "start" ]