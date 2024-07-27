# Homelab

My Home Operations Repository

## Overview

This is a mono repository for my home infrastructure and Kubernetes cluster.

### Installation

```sh
task an:run playbook=cluster-prepare
task an:run playbook=cluster-install

task fl:github-deploy-key
task fl:bootstrap
```
