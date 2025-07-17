FROM node:20-alpine

WORKDIR /app

# Встановити watchman (для кращого live reload) - опціонально
RUN apk add --no-cache bash

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 4200

CMD ["npm", "run", "start", "--", "--host", "0.0.0.0"]
