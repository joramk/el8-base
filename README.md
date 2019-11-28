# CentOS 8 docker base image with systemd [![Build Status](https://travis-ci.com/joramk/el8-base.svg?branch=master)](https://travis-ci.com/joramk/el8-base)
- CentOS 8 base system
- Full systemd support

## Docker run
~~~
docker run -d --tmpfs /run --tmpfs /tmp \
    -v /sys/fs/cgroup:/sys/fs/cgroup:ro \
    joramk/el8-base:latest
~~~
