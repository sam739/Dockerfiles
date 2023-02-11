FROM ubuntu:20.04
ENV REFRESHED 2023-02-11
RUN apt-get update
RUN apt-get -y install redis-server redis-tools

EXPOSE 6379
ENTRYPOINT ["/usr/bin/redis-server"]
CMD []


