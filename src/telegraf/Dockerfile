FROM telegraf:1.12-alpine

RUN apk --no-cache add python3 && pip3 install speedtest-cli

COPY telegraf.conf /etc/telegraf/telegraf.conf
