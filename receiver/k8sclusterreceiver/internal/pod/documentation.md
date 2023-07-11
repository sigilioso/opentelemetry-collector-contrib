[comment]: <> (Code generated by mdatagen. DO NOT EDIT.)

# k8s/pod

**Parent Component:** k8s_cluster

## Default Metrics

The following metrics are emitted by default. Each of them can be disabled by applying the following configuration:

```yaml
metrics:
  <metric_name>:
    enabled: false
```

### k8s.pod.phase

Current phase of the pod (1 - Pending, 2 - Running, 3 - Succeeded, 4 - Failed, 5 - Unknown)

| Unit | Metric Type | Value Type |
| ---- | ----------- | ---------- |
| 1 | Gauge | Int |

## Resource Attributes

| Name | Description | Values | Enabled |
| ---- | ----------- | ------ | ------- |
| k8s.namespace.name | The k8s namespace name. | Any Str | true |
| k8s.node.name | The k8s node name. | Any Str | true |
| k8s.pod.name | The k8s pod name. | Any Str | true |
| k8s.pod.uid | The k8s pod uid. | Any Str | true |
| opencensus.resourcetype | The OpenCensus resource type. | Any Str | true |