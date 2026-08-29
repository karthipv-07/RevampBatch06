FROM node:latest
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 8080
ENTRYPOINT ["node"]
CMD ["server.js", "development"]
