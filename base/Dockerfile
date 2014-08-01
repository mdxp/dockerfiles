FROM debian:wheezy

MAINTAINER Marius Ducea <marius@opscale.com>

ENV HOME /root
ENV DEBIAN_FRONTEND noninteractive

# REPOS uptodate
RUN apt-get update -qq && \
    apt-get upgrade -y \
    apt-get clean

# TOOLS
RUN apt-get install -y -q curl sudo procps
