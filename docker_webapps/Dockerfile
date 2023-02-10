FROM ubuntu:22.04
ENV REFRESHED 2023-02-10

RUN apt-get update
RUN apt-get -y install ruby ruby-dev build-essential redis-tools 
RUN gem install --no-document  sinatra json redis



RUN mkdir -p /opt/webapp

EXPOSE 4567

CMD ["/opt/webapp/bin/webapp"]
