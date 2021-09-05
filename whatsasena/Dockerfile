FROM fusuf/whatsasena:latest

RUN git clone https://github.com/VJXHaCKeR/VJX-BOT-001 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
