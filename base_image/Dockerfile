FROM phusion/baseimage:latest
MAINTAINER Nayeem Syed <developerinlondon@gmail.com>

ADD id_rsa.pub /tmp/host_key
RUN cat /tmp/host_key >> /root/.ssh/authorized_keys && rm -f /tmp/host_key
