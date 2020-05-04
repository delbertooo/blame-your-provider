FROM telegraf:1.14.2

RUN apt-get update && apt-get install -y python3-pip && pip3 install speedtest-cli && rm -rf /var/lib/apt/lists/*

COPY telegraf.conf /etc/telegraf/telegraf.conf
