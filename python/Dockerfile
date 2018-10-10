FROM nvidia/cuda:9.2-cudnn7-devel-ubuntu16.04
MAINTAINER shilfol <yayananoda@gmail.com>

RUN apt-get update -y
RUN apt-get install -y --no-install-recommends \
    vim git python3-dev python3-pip \
    python-wheel python3-setuptools
RUN rm -rf /var/lib/apt/lists/* /var/cache/apt/archives/*
RUN pip3 install --upgrade pip
RUN pip3 install --no-cache-dir cupy-cuda92 ipython numpy matplotlib
