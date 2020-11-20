FROM ubuntu:18.04
WORKDIR /home
RUN apt-get update && \
apt-get install curl \
openjdk-11-jdk \
git \
maven -y && \
adduser --disabled-password --gecos "" Jenkins && \
curl -fsSL https://get.docker.com -o get-docker.sh && \
sh get-docker.sh