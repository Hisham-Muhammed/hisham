FROM fusuf/whatsasena:latest

RUN git clone https://Hisham-Muhammed:mdianajwa4@github.com/Hisham-Muhammed/Sophia-v2

WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
