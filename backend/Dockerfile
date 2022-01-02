FROM node:16

WORKDIR /backend
EXPOSE 3000

COPY package.json package-lock.json .
RUN npm install
COPY app.js .
COPY bin ./bin/
COPY public ./public/
COPY routes ./routes/
COPY views ./views/

CMD DEBUG=backend:* npm start
