FROM redis
MAINTAINER alan
ENV TZ "Asia/Shanghai"
RUN ["mkdir", "-p", "/usr/local/etc/redis/data"]
COPY redis.conf /usr/local/etc/redis/redis.conf
CMD ["redis-server", "/usr/local/etc/redis/redis.conf"]
EXPOSE 6379

