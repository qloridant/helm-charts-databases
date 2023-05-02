# kafka

![Version: 0.2.0](https://img.shields.io/badge/Version-0.2.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 1](https://img.shields.io/badge/AppVersion-1-informational?style=flat-square)

Apache Kafka is an event streaming platform for streaming analytics, data integration.

**Homepage:** <https://kafka.apache.org/>

## Source Code

* <https://github.com/InseeFrLab/helm-charts-datascience/tree/master/charts/kafka>
* <https://github.com/bitnami/charts/tree/master/bitnami/kafka>
* <https://github.com/bitnami/bitnami-docker-kafka>

## Requirements

| Repository | Name | Version |
|------------|------|---------|
| https://charts.bitnami.com/bitnami | kafka | 18.4.2 |
| https://inseefrlab.github.io/helm-charts-interactive-services | library-chart | 1.0.3 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| fullnameOverride | string | `"kafka"` |  |
| kafka.discoverable.allow | bool | `true` |  |
| kafka.fullnameOverride | string | `"kafka"` |  |
| kafka.replicaCount | int | `3` |  |
| kafka.zookeeper.fullnameOverride | string | `"kafka-zookeeper"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.0](https://github.com/norwoodj/helm-docs/releases/v1.11.0)