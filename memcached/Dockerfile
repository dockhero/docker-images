FROM memcached:alpine
HEALTHCHECK CMD /usr/bin/nc -z 127.0.0.1 11211 || exit 1
