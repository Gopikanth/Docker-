
FROM golang:1.16-buster



WORKDIR /go/src/app
COPY ./src .

RUN go get -d -v 
RUN go build -v
RUN echo $PATH
RUN ls
RUN pwd

CMD ["./docker-golang-example"]



