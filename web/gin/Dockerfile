FROM golang:1.12-alpine

ENV GO111MODULE on
WORKDIR /go/app
COPY ./ /go/app

RUN apk --update add --no-cache git