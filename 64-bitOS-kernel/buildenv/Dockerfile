FROM randomdude/gcc-cross-x86_64-elf

RUN sed -i 's/stretch/buster/g' /etc/apt/sources.list && \
    RUN apt-get install -y debian-archive-keyring \
    RUN apt-key update \
    apt-get update && \
    apt-get upgrade -y --allow-unauthenticated && \
    apt-get install -y nasm



#FROM debian:stretch
#
#RUN sed -i 's/deb.debian.org/debian-archive.trafficmanager.net/g' /etc/apt/sources.list
#RUN sed -i 's/security.debian.org/debian-archive.trafficmanager.net/g' /etc/apt/sources.list
#
#RUN apt-get update
#RUN apt-get install -y nasm
#RUN apt-get install -y xorriso
#RUN apt-get install -y grub-pc-bin
#RUN apt-get install -y grub-common
#
#VOLUME /root/env
#WORKDIR /root/env


#FROM randomdude/gcc-cross-x86_64-elf
#
#RUN apt-get update
#RUN apt-get upgrade -y
#RUN apt-get install -y nasm
#RUN apt-get install -y xorriso
#RUN apt-get install -y grub-pc-bin
#RUN apt-get install -y grub-common
#
#VOLUME /root/env
#WORKDIR /root/env