This repository collects Kubernetes manifests, Grafana dashboards, and Prometheus rules combined with documentation and scripts to provide easy to operate end-to-end Kubernetes cluster monitoring with Prometheus using the Prometheus Operator.

The content of this project is written in jsonnet. This project could both be described as a package as well as a library.

Components included in this package:

The Prometheus Operator
Highly available Prometheus
Highly available Alertmanager
Prometheus node-exporter
Prometheus Adapter for Kubernetes Metrics APIs
kube-state-metrics
Grafana
This stack is meant for cluster monitoring, so it is pre-configured to collect metrics from all Kubernetes components. In addition to that it delivers a default set of dashboards and alerting rules. Many of the useful dashboards and alerts come from the kubernetes-mixin project, similar to this project it provides composable jsonnet as a library for users to customize to their needs.



















### Scaling though custom metrics:

![alt text](https://miro.medium.com/max/1400/1*_BdOsoS41c-fYchLimpiAg.jpeg)

### References:

https://towardsdatascience.com/kubernetes-hpa-with-custom-metrics-from-prometheus-9ffc201991e
