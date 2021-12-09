# Serverless

## Overview
![Overview](serverless-overview.png)

## Basic Idea
- Provide validation and modification of data, or check incomming data with business rules
- Identify whether storing data on a DB is feasible or not
- May send information to a online media, like teams or slack

## Challenges
- Installation on local resources are limited, needs CPU and Memory
- Stand-by "can" kills knative running system (resouce problem)
- Knative supports Kafka, but the installation on a Kubernetes Cluster is not that easy

## Walk-Through
- Knative can react on events
- Knative can serve
- Scaling to Zero
call the https://myurl/hello
NAME                                     READY   STATUS
hello-world                              2/2     Running
hello-world                              2/2     Terminating
hello-world                              1/2     Terminating
hello-world                              0/2     Terminating

recall the https://myurl/hello
hello-world                              0/2     Pending
hello-world                              0/2     ContainerCreating
hello-world                              1/2     Running
hello-world                              2/2     Running
