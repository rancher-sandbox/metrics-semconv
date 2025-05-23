# Metrics
- [rancher.managed.cluster](#ranchermanagedcluster) : metric recording each downstream cluster managed by rancher


## rancher.managed.cluster

metric recording each downstream cluster managed by rancher



| Unit | Metric Type | ValueType |
| ---- | ------------ | --------- |
|  | Gauge | int64|

### Attributes

| Name | Description | Type | Required |
|------|-------------|------| ------- |
| controller.managedBy | The name of the controller manager that manages this controller | []string | ❌ |
| k8s.resource.gvk | The group, version, and kind of the Kubernetes resource. | string | ✅ |
| k8s.resource.name | The name of the Kubernetes resource. | string | ✅ |
| k8s.resource.namespace | The namespace of the Kubernetes resource. | string | ✅ |
| rancher.cluster.id | The internal id of the cluster in rancher | string | ✅ |
| rancher.k8s.distribution | The Kubernetes distribution of the cluster. | string | ✅ |

