FROM quay.io/ajusk/lisa
RUN git clone https://github.com/ajusk/LISA /root/ajusk/
WORKDIR /root/Abu/
RUN yarn install --network-concurrency 1
CMD ["node", "index.js"]
