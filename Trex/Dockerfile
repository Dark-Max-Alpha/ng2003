FROM node:latest

RUN git clone https://github.com/Dark-Max-Alpha/ng2003
WORKDIR /root/ng2003/
RUN git clone https://github.com/Dark-Max-Alpha/ng2003
ENV TZ=Asia/Colombo
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
