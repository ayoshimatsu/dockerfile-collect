FROM ubuntu:16.04
RUN apt-get update
RUN apt-get install -y nfs-common
RUN apt-get install -y cifs-utils
RUN apt-get install -y vim
RUN apt-get install -y iputils-ping net-tools
RUN echo "192.168.208.120:/share_export /mnt nfs rw,auto 0 0" >> /etc/fstab
