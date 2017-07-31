Collecting Docker Log Files with Fluentd and Elasticsearch

This directory contains the source files needed to make a Docker image that collects Docker container log files using Fluentd and sends them to an instance of Elasticsearch. This image is designed to be used as part of the Kubernetes cluster bring up process. The image resides at DockerHub under the name kubernetes/fluentd-elasticsearch.