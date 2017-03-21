FROM redis:3.2.8-alpine

ADD rootfs /

WORKDIR /data

VOLUME /data

CMD [ "redis-server", "/usr/local/redis/redis.conf" ]
