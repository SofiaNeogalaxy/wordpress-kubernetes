# Kubernetes WordPress Deployment with Amazon EFS and Redis

This project demonstrates how to deploy a WordPress application and a stateless backend application that uses Redis as its database on a Kubernetes cluster. The WordPress application is backed by a MySQL database, and use Amazon EFS storage to provide shared storage across cluster's nodes.

### Project Overview
The project includes the following directories and files:

- efk-stack/: This directory contains files used to deploy the Elasticsearch, Fluentd, and Kibana (EFK) stack, which is an open-source tool used to collect, store, and visualize logs in Kubernetes clusters.

- k8s-dashboard/: This directory contains the configuration files for the Kubernetes dashboard.

- k8s-efs/: This directory contains files related to using Amazon Elastic File System (EFS) with Kubernetes.

- k8s-stateless-backend/: This directory contains YAML files defining Kubernetes deployments and services for a stateless backend application using Redis as a database.
