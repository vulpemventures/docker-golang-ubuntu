FROM ubuntu:20.04


ENV GOLANG_VERSION 1.15.7

# Install wget
RUN apt update && apt install -y build-essential wget
# Install Go
RUN wget https://golang.org/dl/go${GOLANG_VERSION}.linux-amd64.tar.gz
RUN tar -C /usr/local -xzf go${GOLANG_VERSION}.linux-amd64.tar.gz
RUN rm -f go${GOLANG_VERSION}.linux-amd64.tar.gz

ENV PATH "$PATH:/usr/local/go/bin"