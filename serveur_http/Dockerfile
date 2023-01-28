FROM alpine:3.14
RUN apk add -u npm
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 80
CMD ["npm", "start"]
