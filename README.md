# RDB real time data ingestion
RDB real time ingestion to data lake using [debezium](https://debezium.io), [kafka](https://kafka.apache.org), [flink](https://flink.apache.org) and [hudi](https://hudi.apache.org).

## Infrastructure

- [minikube](https://minikube.sigs.k8s.io)
- [helm](https://helm.sh)
- [strimzi](https://strimzi.io)

## Frameworks, libraries and platforms

- [debezium](https://debezium.io)
- [kafka](https://kafka.apache.org)
- [apache flink](https://flink.apache.org)
- [hudi](https://hudi.apache.org)
- [schema registry by confluent](https://docs.confluent.io/platform/current/schema-registry/index.html)

## Run

### Run helm using docker
Use [k8s](https://github.com/alpine-docker/k8s) docker image for run various cli for kubernetes.

```shell
docker run -it --rm --name k8s alpine/k8s 
```