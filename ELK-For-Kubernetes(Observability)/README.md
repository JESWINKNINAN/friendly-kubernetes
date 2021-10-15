## Introduction

* Introduction to Observability(3 Pillers - Logs, Traces, Metrics)
* Elastic Stack [Beats, Agents, Logstash, Kinesis, Kafka, Object Storages]

## Part 1: ELK Running on Kubernetes

- Why we need ELK for Kubernetes ? (Observability Platforms)
- Running ELK on Kubernetes.
  * Introduction to ECK Operator(OSS).
    - Refer the following:
      * https://github.com/elastic/cloud-on-k8s
      * https://www.elastic.co/guide/en/cloud-on-k8s/current/index.html
  * Elastic Stack Deployment using ECK Operator     
    - [elastic-with-data-tiers.yaml](https://github.com/JESWINKNINAN/friendly-kubernetes/blob/main/ELK-For-Kubernetes(Observability)/elastic-with-data-tiers.yaml)
    - [kibana.yaml](https://github.com/JESWINKNINAN/friendly-kubernetes/blob/main/ELK-For-Kubernetes(Observability)/kibana.yaml)
  * Agents Stack Deployment using ECK Operator.
    - [filebeat.yaml](https://github.com/JESWINKNINAN/friendly-kubernetes/blob/main/ELK-For-Kubernetes(Observability)/filebeat.yaml)
    - [metricbeat.yaml](https://github.com/JESWINKNINAN/friendly-kubernetes/blob/main/ELK-For-Kubernetes(Observability)/metricbeat.yaml)
  * Kafka into Elastic Stack for optimal perfomance and staging data.
- Entire stack can be Gitops driven.  
- Optional: Monitoring Cluster For Elastic Stack     
  
## Part 2: Collecting Your First Pod Logs(Workflow)



### Log Collection
- Filebeats, Fluentbit can be used to collect the Kubernetes Logs by running Filebeat, Fluentbit or any ECS supported forwarders. 
- Fluentbit is a Log Processor and Forwarder which allows you to collect any data like metrics and logs from different sources, enrich them with filters and send them to multiple destinations(Refer: https://github.com/fluent/fluent-bit)
- Forwarded logs will be pushed to the any of the integration as mentioned below. 

```
Filebeat -> Kafka/Kinesis
Filebeat -> Logstash
Fluentbit -> Kafka/Kinesis
Fluentbit -> Logstash
```

### Log Processing. 
- Filebeats or any agents will ships the logs to Kafka

### Visulization


## Part 3: Collecting Your First Pod Metrics(Workflow)

### Metric Collection

### Metric Processing

### Visulization

## References

- [Elastic Cloud on Kubernetes](https://github.com/elastic/cloud-on-k8s)
- [Elastic Cloud on Kubernetes-Official Docs](https://www.elastic.co/guide/en/cloud-on-k8s/current/index.html)

**More details**

- [DevOps Malayalam](https://devopsmalayalam.io)
- [CNCF Community Trivandrum](https://community.cncf.io/trivandrum/)
