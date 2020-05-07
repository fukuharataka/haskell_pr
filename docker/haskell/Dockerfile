FROM centos:centos7

RUN curl -sSL https://get.haskellstack.org/ | sh

RUN stack upgrade
RUN stack --version # build時に確かめられるように

RUN stack setup