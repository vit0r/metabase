FROM alpine:3.20.3

RUN apk update;apk add curl postgresql16-client
RUN psql --version
ADD entrypoint.sh /entrypoint
RUN chmod +x /entrypoint
ENTRYPOINT [ "/entrypoint" ]