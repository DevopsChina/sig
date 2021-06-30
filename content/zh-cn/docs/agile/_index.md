---
title: "敏捷道场"
linkTitle: "Agile"
description: "The GitOps Toolkit documentation."
weight: 60
---

## 简介

The GitOps Toolkit is the set of APIs and controllers that make up the
runtime for Flux v2. The APIs comprise Kubernetes custom resources,
which can be created and updated by a cluster user, or by other
automation tooling.

## 导师

* 悟空
* 如来
* 观音

You can use the toolkit to extend Flux, and to build your own systems
for continuous delivery. The [the source-watcher
guide](../gitops-toolkit/source-watcher/) is a good place to start.

## 日常修炼

### 例会

### Demo Day

### Game Day

### XXXX Day


推荐外部资源：

- [Source Controller](source/_index.md)
    - [GitRepository CRD](source/gitrepositories.md)
    - [HelmRepository CRD](source/helmrepositories.md)
    - [HelmChart CRD](source/helmcharts.md)
    - [Bucket CRD](source/buckets.md)
- [Kustomize Controller](kustomize/_index.md)
    - [Kustomization CRD](kustomize/kustomization.md)
- [Helm Controller](helm/_index.md)
    - [HelmRelease CRD](helm/helmreleases.md)
- [Notification Controller](notification/_index.md)
    - [Provider CRD](notification/provider.md)
    - [Alert CRD](notification/alert.md)
    - [Receiver CRD](notification/receiver.md)
- [Image automation controllers](image/_index.md)
    - [ImageRepository CRD](image/imagerepositories.md)
    - [ImagePolicy CRD](image/imagepolicies.md)
    - [ImageUpdateAutomation CRD](image/imageupdateautomations.md)
