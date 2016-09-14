FROM outstand/ruby-plus:2.1.10
MAINTAINER Ryan Schlesinger <ryan@outstand.com>

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
        qt5-default \
        libqt5webkit5-dev \
        gstreamer1.0-plugins-base \
        gstreamer1.0-tools \
        gstreamer1.0-x \
        xvfb \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
