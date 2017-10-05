
FROM alpine:3.6
MAINTAINER Max Belyanin <maxbelyanin@gmail.com>

RUN apk add --no-cache isc-dhcp-server

ENTRYPOINT ["dhcpd", "-d", "--no-pid"]
