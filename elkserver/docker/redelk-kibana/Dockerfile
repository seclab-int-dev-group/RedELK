#
# Part of RedELK
# Dockerfile for RedELK Kibana image
#
# Authors:
# - Outflank B.V. / Marc Smeets
# - Lorenzo Bernardi
#

FROM docker.elastic.co/kibana/kibana:7.17.9
LABEL maintainer="Outflank B.V. / Marc Smeets"
LABEL description="RedELK Kibana"

#COPY redelk-7.10.0.zip /tmp/redelk-7.10.0.zip
#RUN /usr/share/kibana/bin/kibana-plugin install file:/tmp/redelk-7.10.0.zip

RUN /usr/share/kibana/bin/kibana-plugin install  https://github.com/fastlorenzo/redelk-kibana-app/releases/download/v1.0.0/redelk-7.17.9.zip
