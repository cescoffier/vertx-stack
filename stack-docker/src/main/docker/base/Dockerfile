# A base Dockerfile for Vert.x 3

FROM java:8

MAINTAINER Clement Escoffier <clement@apache.org>

COPY ./usr /usr/

# Set path
ENV VERTX_HOME /usr/local/vert.x-${project.version}
ENV PATH $VERTX_HOME/bin:$PATH
