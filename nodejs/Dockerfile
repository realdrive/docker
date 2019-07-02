FROM node:8.8.1
RUN mkdir -p /root/node
WORKDIR /root/node
ADD app.js /root/node/
ADD cron.yaml /root/node/
ADD index.html /root/node/
ADD package.json /root/node/
CMD ["npm","run","start"]
