FROM fusuf/whatsasena:latest

RUN git clone https://github.com/jesonpro/Kavindya-X/root/ales
WORKDIR /root/ales/
RUN git clone https://github.com/Kavindya-X/Config
RUN git clone https://github.com/Kavindya-X/Angela-x
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "main.js"]
