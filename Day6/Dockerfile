FROM node:12.18.1

RUN makedir Day6
WORKDIR /Day6
COPY server.js /Day6

RUN npm install express

CMD [ "node", "server.js" ]

EXPOSE 3000
