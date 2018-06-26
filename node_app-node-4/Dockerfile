FROM node:4.2.3

EXPOSE 3000
EXPOSE 5858

COPY . /usr/src/app
WORKDIR /usr/src/app

RUN cd /usr/src/app && npm install

CMD ["node", "--debug=5858", "index.js"]
