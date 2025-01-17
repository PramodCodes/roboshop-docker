FROM node:18
EXPOSE 8080
# changing work directory to opt/server everything will happend in WORKDIR
WORKDIR /opt/server
ENV MONGO=true
COPY package.json /opt/server/
COPY server.js /opt/server/
RUN npm install

CMD ["node", "server.js"]