FROM docker.elastic.co/kibana/kibana:7.9.2

ENV ELASTICSEARCH_HOSTS='http://localhost:9200' ELASTICSEARCH_USERNAME=${es_username} ELASTICSEARCH_PASSWORD=${es_password} xpack.security.enabled=true

EXPOSE 5601