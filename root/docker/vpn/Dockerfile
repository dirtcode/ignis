FROM ubuntu:18.04
RUN apt-get update \
	&& apt-get install -y openvpn 
#	&& cp au.protonvpn.com.udp1194.ovpn /etc/openvpn/client \
#	&& cp login.key /etc/openvpn/client
WORKDIR /etc/openvpn/client
COPY au.protonvpn.com.udp1194.ovpn /etc/openvpn/client
COPY login.key /etc/openvpn/client
#CMD ["openvpn", "--cd", "/etc/openvpn", "--config", "au.protonvpn.com.udp1194.ovpn"]
