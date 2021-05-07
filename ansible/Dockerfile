FROM ubuntu:20.04
LABEL authors="Justin Roysdon"

RUN apt-get update \
	&& apt-get -y upgrade \
	&& apt-get install -y net-tools ansible ssh-client

COPY hosts /etc/ansible/
#COPY playbooks /container/ansible/
#COPY sample-playbooks /container/ansible/
WORKDIR /container/ansible
