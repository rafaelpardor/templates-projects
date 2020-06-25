# UWUntu
FROM ubuntu:18.04
MAINTAINER @rafaelpardor

RUN apt update -y; apt upgrade -y
RUN apt install -y -q git \
  tmux \
  curl \
  wget && \
  rm -rf /var/lib/apt/lists/* && \
  apt clean

CMD ["/bin/bash"]

