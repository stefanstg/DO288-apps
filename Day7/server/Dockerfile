FROM node:12.18.1

COPY /server.js /Day7/server/server.js
WORKDIR /Day7/server/

RUN npm install express
RUN npm install mysql

CMD [ "node", "server.js" ]

EXPOSE 3000
