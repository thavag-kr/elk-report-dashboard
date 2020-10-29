# elk-report-dashboard

This repo will help in setting up a local elk reporting structure for publishing zerocode csv or json files.

The results are picked up by logstash and sent over to Elasticsearch.
Visualization is done in Kibana dashboards.

Some sample report files and config files are provided.

Also the docker compose uses a custom docker images that are hosted in dockerhub. 

Please use the Docker files if you need to create your own image, they are provided under each service folder.


To Start elasticsearch and Kibana:
    $docker-compose up -d kibana
    
To Start Logstash:
    $docker-compose up -d logstash

To view the data in kibana navigate to localhost:5601 or kibana:5601.
