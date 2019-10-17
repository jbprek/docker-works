# my-ubuntu image
#
# Build using :
# docker build -t jbprek/ubuntu-utils:1.0 .
#
FROM ubuntu:bionic
RUN apt-get  update -y \
    && apt-get upgrade -y \
    && apt-get install iputils-ping -y \
    && apt-get install net-tools -y
CMD bash