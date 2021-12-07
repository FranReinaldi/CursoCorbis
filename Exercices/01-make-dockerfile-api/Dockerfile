FROM golang:1.14

WORKDIR /go/src/app

EXPOSE 5000

COPY main.go /go/src/app/


RUN go get -d -v ./...

RUN go install -v ./...

ENTRYPOINT ["app"]