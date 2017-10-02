FROM outstand/ruby-plus:2.4.2
MAINTAINER Ryan Schlesinger <ryan@outstand.com>

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
        mysql-client \
        redis-tools \
        qt5-default \
        libqt5webkit5-dev \
        gstreamer1.0-plugins-base \
        gstreamer1.0-tools \
        gstreamer1.0-x \
        xvfb \
        xauth \
        x11-utils \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
