FROM ubuntu

RUN apt update

RUN apt install nmap -y

WORKDIR /usr/bin

ENTRYPOINT ["/usr/bin/nmap"]
