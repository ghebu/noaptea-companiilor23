FROM alpine:latest

ENV AWS_VERSION=2.12.3
RUN apk update && \
    apk upgrade && \
    apk add python3 py3-pip groff 

RUN pip3 install awscli --upgrade --user 

ENTRYPOINT ["/root/.local/bin/aws"]

