# CentOS 7 docker base image with systemd [![Build Status](https://travis-ci.org/joramk/el7-base.svg?branch=master)](https://travis-ci.org/joramk/el7-base)
- CentOS 7 base system
- Full systemd support

## Docker run
~~~
docker run -d --tmpfs /run --tmpfs /tmp \
    -v /sys/fs/cgroup:/sys/fs/cgroup:ro \
    joramk/el7-base:latest
~~~
