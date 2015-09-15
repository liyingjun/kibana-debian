# kibana-debian
Debian 8 source package source for Kibana 4 deployment.

## Instructions

1. Download and extract the kibana source release 4.1.1
2. cd kibana
3. git clone git@github.com:mkhpalm/kibana-debian.git debian
4. debuild
5. dpkg -i ../kibana*.deb
6. https://localhost:5601
