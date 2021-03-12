# helm-charts
Helm charts for open source applications - ready to use for deployment on Kubernetes 

## TL;DR

```bash
$ helm repo add mayadata https://mayadata-io.github.io/helm-charts/
$ helm repo update
```

## Introduction

This repository contains various Helm charts for stateful open source workloads.

## Prerequisites

- Helm 3.x

## Adding this helm repository

To add this repository to the helm configuration:

```bash
$ helm repo add mayadata https://mayadata-io.github.io/helm-charts/
```

## Using this Helm repository

To install a chart from this repository (example with Wordpress):

```bash
$ helm install my-wordpress mayadata/wordpress
```

## Removing this Helm repository

To remove the helm repository from helm configuration:

```bash
$ helm repo remove mayadata
```
