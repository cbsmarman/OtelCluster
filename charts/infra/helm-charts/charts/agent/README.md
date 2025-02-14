# agent

![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 0.6.0](https://img.shields.io/badge/AppVersion-0.6.0-informational?style=flat-square)

Chart to install K8s collection stack based on Observe Agent

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| Observe | <support@observeinc.com> |  |

## Requirements

| Repository | Name | Version |
|------------|------|---------|
| file://charts/daemonset | daemonset | 0.1.0 |
| file://charts/deployment | deployment | 0.1.0 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| daemonset.daemonset.resources.limits.cpu | string | `"250m"` |  |
| daemonset.daemonset.resources.limits.memory | string | `"256Mi"` |  |
| daemonset.daemonset.resources.requests.cpu | string | `"250m"` |  |
| daemonset.daemonset.resources.requests.memory | string | `"256Mi"` |  |
| deployment.deployment.resources.limits.cpu | string | `"250m"` |  |
| deployment.deployment.resources.limits.memory | string | `"256Mi"` |  |
| deployment.deployment.resources.requests.cpu | string | `"250m"` |  |
| deployment.deployment.resources.requests.memory | string | `"256Mi"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.14.2](https://github.com/norwoodj/helm-docs/releases/v1.14.2)
