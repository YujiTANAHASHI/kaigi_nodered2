FROM nodered/node-red-docker

RUN npm install googleapis@27 --save
RUN npm install fs
RUN npm install readline
RUN npm install bcryptjs

COPY settings.js /data/
COPY flows.json /data/