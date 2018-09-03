FROM mongo:3.4.1
MAINTAINER Jia Chenhui
ENV REFRESHED_AT 2017-07-27

ADD . /replicaset
WORKDIR /replicaset

RUN mkdir -p /replicaset/data/db

EXPOSE 27017
ENTRYPOINT [ "mongod", "--replSet", "my-mongo-set" ]