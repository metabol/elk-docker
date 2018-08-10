# Elasticsearch, Logstash, Kibana (ELK) Docker image

[![](https://images.microbadger.com/badges/image/sebp/elk.svg)](https://microbadger.com/images/sebp/elk "Get your own image badge on microbadger.com") [![Documentation Status](https://readthedocs.org/projects/elk-docker/badge/?version=latest)](http://elk-docker.readthedocs.io/?badge=latest)

This Docker image provides a convenient centralised log server and log management web interface, by packaging Elasticsearch, Logstash, and Kibana, collectively known as ELK.

### Documentation

See the [ELK Docker image documentation web page](http://elk-docker.readthedocs.io/) for complete instructions on how to use this image.




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

Written by [Sébastien Pujadas](https://pujadas.net), released under the [Apache 2 license](https://www.apache.org/licenses/LICENSE-2.0).

Edited by Metabol 2018-08-10
