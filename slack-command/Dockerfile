FROM node:6.9.4

RUN git clone https://github.com/ozcn/zenos-slack.git

RUN cd zenos-slack && npm install

ENTRYPOINT ["node", "zenos-slack/index.js"]
