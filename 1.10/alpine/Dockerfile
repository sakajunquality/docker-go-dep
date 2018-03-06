FROM golang:1.10-alpine
RUN apk --update add pcre-dev openssl-dev \
  && apk add --virtual build-dependencies build-base curl git

RUN curl -SLO https://github.com/golang/dep/releases/download/v0.4.1/dep-linux-amd64 \
  && mv dep-linux-amd64 /go/bin/dep \
  && chmod +x /go/bin/dep
