FROM ubuntu:latest
MAINTAINER darwinsubarmaniam@googlemail.com
RUN apt-get update && apt-get upgrade -y
RUN apt-get install -y \nginx \git
RUN mkdir .p /root/.ssh/
ADD ./id_rsa /root/.ssh/id_rsa
RUN git@gitlab.com:vcloudex/serverconfig.git
RUN cd /home
RUN git clone https://darwinsubramaniam@gitlab.com/vcloudex/serverconfig.git
RUN cd serverconfig/Master_Site-enabled


