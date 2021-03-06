# Elasticsearch, Logstash, Kibana (ELK) Docker image
Collect, search and visualise log data with ELK (Elasticsearch 6.3.2, Logstash 6.3.2, Kibana 6.3.2).

This Docker image provides a convenient centralised log server and log management web interface, by packaging Elasticsearch, Logstash, and Kibana, collectively known as ELK.

### Documentation

See the [ELK Docker image documentation web page](http://elk-docker.readthedocs.io/) for complete instructions on how to use this image.


See the [standalone Installation Documentation ](https://logz.io/learn/complete-guide-elk-stack/)

#Testing Services
- Kibana http://localhost:5601
- ElasticSearch http://localhost:9200
- Logstash http://localhost:9600
- FileBeat http://localhost:5044

*Remember to open ports if necessary


### Important 
In case of the following errors
1) Docker daemon failed to create tcp 0.0.0.0:xxxxxxxx
 - Restart the docker daemon
 
2)Elastic cluster failed to start
 - Check ES_JVM_OPTS in Elasticseach-default.conf 



### Docker Hub

This image is hosted on Docker Hub at [https://hub.docker.com/r/sebp/elk/](https://hub.docker.com/r/sebp/elk/

**Note** – See the documentation page for more information on pulling specific combinations of versions of Elasticsearch, Logstash and Kibana.

### About

Released under the [Apache 2 license](https://www.apache.org/licenses/LICENSE-2.0).

By Metabol 2018-08-10
