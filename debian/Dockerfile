# Murmur
#
# use debian base image by debian
#
FROM debian:jessie
MAINTAINER Ken Dilley, vanceavalon@gmail.com
RUN apt-get update
RUN apt-get install mumble-server -y
EXPOSE 64738
ADD mumble-server.ini /etc/mumble-server.ini
CMD murmurd -fg -ini /etc/mumble-server.ini
