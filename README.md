# scrs-elk-reporting

This repo will help in setting up a local elk reporting structure for publishing zerocode csv or json files.

The results are picked up by logstash and sent over to Elasticsearch.
Visualization is done in Kibana dashboards.

Some sample report files and config files are provided.

Also the docker compose uses a custom docker images that are hosted in scrsregistry. Docker files are provided

To Execute: $docker-compose up -d
