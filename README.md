# elk-tls-docker

![](https://raw.githubusercontent.com/wiki/swimlane/elk-tls-docker/images/elk-tls-docker-diagram.png)

This docker-compose project will assist with setting up and creating a ELK stack using either self-signed TLS certificates or using LetsEncrypt certificates for communications.  In general you get HTTPS for all services.

> Please checkout our [WiKi](https://github.com/swimlane/elk-tls-docker/wiki) for detailed explanation of the project structure, configuration settings, and more.

## Environment Details

This project was built so that you can test and use built-in features under Elastic Security, like detections, signals, cases, and other features.

This docker-compose project will create the following Elastic containers based on version 7.12.0:

* Elasticsearch
* Logstash
* Kibana
* Packetbeat
* Filebeat
* Elastic Agent (Ubuntu 20.04)
* Metricbeat

