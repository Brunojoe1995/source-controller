# source.toolkit.fluxcd.io/v1beta2

This is the v1beta2 API specification for defining the desired state sources of Kubernetes clusters.

## Specification

* Source kinds:
  + GitRepository
  + HelmRepository
  + HelmChart
  + [Bucket](buckets.md)
  
## Implementation

* [source-controller](https://github.com/fluxcd/source-controller/)

## Consumers

* [kustomize-controller](https://github.com/fluxcd/kustomize-controller/)
* [helm-controller](https://github.com/fluxcd/helm-controller/)
