FROM node:14.18.1-alpine
WORKDIR /frontend
ADD *.json ./
RUN npm install
ADD . .
RUN npm run build
EXPOSE 6001
ENV NUXT_HOST=0.0.0.0
ENV NUXT_PORT=6001