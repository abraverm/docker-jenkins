FROM abraverm/jenkins:node
MAINTAINER Alexander Braverman Masis <abraverm@redhat.com>

RUN yum install -y docker-io libcgroup python-pip dnsmasq sshpass
RUN pip install -U docker-compose
RUN echo "user=root" >> /etc/dnsmasq.conf
