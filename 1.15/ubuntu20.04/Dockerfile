FROM ubuntu:20.04

ENV PATH /usr/local/go/bin:$PATH

ENV GOLANG_VERSION 1.15.7

# Install wget
RUN apt update && apt install -y wget
# Install Go
RUN wget https://golang.org/dl/go${GOLANG_VERSION}.linux-amd64.tar.gz
RUN tar -C /usr/local -xzf go${GOLANG_VERSION}.linux-amd64.tar.gz

