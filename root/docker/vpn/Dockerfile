FROM ubuntu:18.04
RUN apt-get update && apt-get install -y openvpn
WORKDIR /etc/openvpn
COPY au.protonvpn.com.udp1194.ovpn /etc/openvpn
COPY login.key /etc/openvpn
#CMD ["openvpn", "--cd", "/etc/openvpn", "--config", "au.protonvpn.com.udp1194.ovpn"]

