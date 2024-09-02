# Standard Prometheus Exporters

This repository contains a curated list of standard Prometheus exporters for various components and services. These exporters allow you to collect metrics from different systems and expose them in a format that Prometheus can scrape.



## Standard Prometheus Exporters

| Component | Exporter | Description |
|-----------|----------|-------------|
| Linux/Unix Systems | [Node Exporter](https://github.com/prometheus/node_exporter) | Hardware and OS metrics for *NIX kernels |
| Windows Systems | [Windows Exporter](https://github.com/prometheus-community/windows_exporter) | Windows system metrics |
| MySQL | [MySQL Exporter](https://github.com/prometheus/mysqld_exporter) | MySQL server metrics |
| PostgreSQL | [PostgreSQL Exporter](https://github.com/prometheus-community/postgres_exporter) | PostgreSQL database metrics |
| MongoDB | [MongoDB Exporter](https://github.com/percona/mongodb_exporter) | MongoDB metrics |
| Apache HTTP Server | [Apache Exporter](https://github.com/Lusitaniae/apache_exporter) | Apache HTTP server metrics |
| Nginx | [Nginx Exporter](https://github.com/nginxinc/nginx-prometheus-exporter) | Nginx web server metrics |
| RabbitMQ | [RabbitMQ Exporter](https://github.com/rabbitmq/rabbitmq-prometheus) | RabbitMQ metrics |
| Kafka | [Kafka Exporter](https://github.com/danielqsj/kafka_exporter) | Kafka broker and consumer group metrics |
| AWS CloudWatch | [CloudWatch Exporter](https://github.com/prometheus/cloudwatch_exporter) | Amazon Web Services CloudWatch metrics |
| Google Cloud Platform | [Stackdriver Exporter](https://github.com/prometheus-community/stackdriver_exporter) | Google Cloud Platform Stackdriver metrics |
| Microsoft Azure | [Azure Exporter](https://github.com/RobustPerception/azure_metrics_exporter) | Microsoft Azure metrics |
| HAProxy | [HAProxy Exporter](https://github.com/prometheus/haproxy_exporter) | HAProxy load balancer metrics |
| Redis | [Redis Exporter](https://github.com/oliver006/redis_exporter) | Redis database metrics |
| Elasticsearch | [Elasticsearch Exporter](https://github.com/prometheus-community/elasticsearch_exporter) | Elasticsearch metrics |
| JMX | [JMX Exporter](https://github.com/prometheus/jmx_exporter) | Metrics from applications exposing JMX metrics |
| Blackbox Exporter | [prometheus/blackbox_exporter](https://github.com/prometheus/blackbox_exporter) | Probing of HTTP/HTTPS, DNS, TCP and ICMP endpoints |
| Kafka Exporter |  [danielqsj/kafka_exporter](https://github.com/danielqsj/kafka_exporter) | Kafka metrics |


### Guide
[Best practices using prometheus exporters](https://last9.io/blog/best-practices-using-and-writing-prometheus-exporters/)

## Contributing

If you know of any other standard Prometheus exporters that should be added to this list, please feel free to create a pull request or open an issue.
