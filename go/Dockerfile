FROM golang:alpine

WORKDIR /build
COPY go.mod /build
COPY go.sum /build
RUN go mod download