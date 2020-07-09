ARG ARCH=
# FROM ${ARCH}debian:buster-slim
FROM ${ARCH}centos:7 AS prep_files

RUN yum update -y && yum install -y tar gzip curl && yum clean all

ENTRYPOINT [ "curl" ]

