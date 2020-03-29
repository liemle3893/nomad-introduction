# Introduction

Even k8s is dominant in field of container orchestration but that does not let HashiCorp felt down. HashiCorp has created there own Workload Orchestrator, I mean, every workload can be scheduled and managed no matter that was binary or containerized application. That is amazing!

[HashiCorp Nomad](https://nomadproject.io) is the project that made manages and migrates legacy application to the cloud more easily.

## Requirement:

Your PC must have these software installed:

- `vagrant`
- `virtualbox`

## In this repo

- [Slides](./slides) contains the slide which I used to present.
- [Standalone](./standalone) in this repo where I boostrapped two nomad, 1 master and 1 slave, they was configured to to form a cluster directly.
- [Consul Integration](./consul-integration) enabled service discovery and self discovery between nomad nodes via Consul. These node will automically form a cluster like Black Magic
- [Advanced](./advanced) This repo was a copy of [this](https://github.com/microservices-demo/microservices-demo.git). I just upgrade and reconfig to made sure their demo work. I will make a PR ASAP to them after I cleanup my code.

To know how to run these example, please see README.ME files.
