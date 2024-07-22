FROM alpine:latest

RUN apk add --no-cache bash

COPY . /opt/adabasdb

WORKDIR /opt/adabasdb

CMD ["./start.sh"]
