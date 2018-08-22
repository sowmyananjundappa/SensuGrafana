# SensuGrafana
Sensu with Grafana using Docker

Installation Guide

docker-compose up -d

./run-client.sh

Login Information

RabbitMQ

Note: When changing RabbitMQ configurations, you'll want to make sure that the configuration for sensu (rabbitmq.json) reflects the changes made.

VHost: /sensu

Username: sensu

Password: secret

Graphite

Username: admin

Password: admin

Grafana
Username: admin

Password: admin

Ports:

Service	Port

Uchiwa Web Dashboard	3000

Grafana Web Dashboard	3030

Graphite Data UI	8080
