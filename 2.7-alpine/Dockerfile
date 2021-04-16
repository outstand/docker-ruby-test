FROM outstand/ruby-plus:2.7.3-alpine
MAINTAINER Ryan Schlesinger <ryan@outstand.com>

RUN apk add --no-cache \
      mysql-client \
      redis \
      mariadb-dev \
      tzdata

ENV DOCKERIZE_VERSION v0.6.1
RUN wget https://github.com/jwilder/dockerize/releases/download/$DOCKERIZE_VERSION/dockerize-alpine-linux-amd64-$DOCKERIZE_VERSION.tar.gz \
    && tar -C /usr/local/bin -xzvf dockerize-alpine-linux-amd64-$DOCKERIZE_VERSION.tar.gz \
    && rm dockerize-alpine-linux-amd64-$DOCKERIZE_VERSION.tar.gz
