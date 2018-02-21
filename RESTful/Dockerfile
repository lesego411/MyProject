FROM ubuntu:0458a4468cbc
MAINTAINER Lesego <lesegoalex@gmail.com>

RUN apk add --update -t build-deps curl go git libc-dev gcc libgcc
RUN go get github.com/russross/blackfriday github.com/gorilla/mux

ADD /https://lesego411@bitbucket.org/lesego411/restful.git/

EXPOSE 8080

CMD ["go", "run", "main.go"]
