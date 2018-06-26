FROM node:10

EXPOSE 3000
EXPOSE 9229

COPY . /usr/src/app
WORKDIR /usr/src/app

RUN cd /usr/src/app && npm install

CMD ["node", "--inspect=0.0.0.0:9229", "index.js"]
