FROM node:16

WORKDIR /app
EXPOSE 3000

COPY node_modules package-lock.json package.json ./
RUN npm install
CMD ["npx", "nodemon", "app.js"]
