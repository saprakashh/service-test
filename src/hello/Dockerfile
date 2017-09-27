FROM ubuntu

RUN apt update && apt-get install -y golang-go

ENV GOROOT=/usr/lib/go/ \
    GOPATH=/go/ \
    PATH=$GOPATH/bin:$GOROOT/bin:$PATH
    
WORKDIR /go
