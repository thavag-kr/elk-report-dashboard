FROM docker.elastic.co/elasticsearch/elasticsearch:7.9.2

ENV discovery.type=single-node ES_JAVA_OPTS="-Xmx2g -Xms2g"

CMD [docker run /bin/bash -c "--ulimit nofile=65536:65536"]