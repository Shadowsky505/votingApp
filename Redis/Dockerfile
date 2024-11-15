FROM alpine:latest

RUN apk add --no-cache redis

RUN mkdir -p /etc/redis

COPY redis.conf /etc/redis/redis.conf

EXPOSE 6379

CMD ["redis-server", "/etc/redis/redis.conf"]
