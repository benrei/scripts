# ELK - Elastic stack

## Install Elasticsearch
> wget -O - https://raw.githubusercontent.com/benrei/scripts/master/elk/install_elasticsearch.sh | sudo bash

## Install Logstash
Note: Require [Install Elasticsearch](#-Install-Elasticsearch) first
> wget -O - https://raw.githubusercontent.com/benrei/scripts/master/elk/install_logstash.sh | sudo bash

Logstash should not be startet before a `pipeline` is set up
> sudo service logstash start

## Install Kibana
Note: Require [Install Elasticsearch](#-Install-Elasticsearch) first
> wget -O - https://raw.githubusercontent.com/benrei/scripts/master/elk/install_kibana.sh | sudo bash