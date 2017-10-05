
FROM ubuntu:xenial
MAINTAINER Max Belyanin <maxbelyanin@gmail.com>

RUN apt-get update \
 && apt-get install -y isc-dhcp-server \
 && rm -rf /var/lib/apt/lists/*

ENTRYPOINT ["/usr/sbin/dhcpd", "-d", "--no-pid"]
