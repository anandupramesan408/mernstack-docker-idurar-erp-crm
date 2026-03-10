FROM node:21
WORKDIR /app
COPY  . .
RUN npm install
EXPOSE 8888
CMD ["sh","-c","npm run setup && npm run dev"]