# docker build -t hackbox .
# docker run -it hackbox /bin/bash

FROM ubuntu:latest
RUN apt update && apt upgrade -y
RUN apt install -y nmap curl git vim python3 openvpn wget net-tools
RUN useradd -d /home/punk/ -m -p punk -s /bin/bash punk
RUN echo "punk:punk" | chpasswd
RUN chown -R punk:punk /opt
