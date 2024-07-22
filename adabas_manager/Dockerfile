FROM alpine:latest

RUN apk add --no-cache bash

COPY . /opt/adabas_manager

WORKDIR /opt/adabas_manager

CMD ["./start.sh"]
