FROM node:13-alpine

WORKDIR /usr/user-portal-frontend

COPY . .

RUN npm install

RUN npm run build

expose 3002

# Run the application
CMD ["sh","-c", "npm start"]

