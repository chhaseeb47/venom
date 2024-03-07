FROM quay.io/chhaseeb47/venom:beta
RUN git clone https://github.com/chhaseeb47/venom /root/chhaseeb47/venom
WORKDIR /root/chhaseeb47/venom
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
