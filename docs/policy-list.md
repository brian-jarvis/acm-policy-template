# Policy list and details
This doc gives a listing of all policies in the repo along with a brief description

**Table of Contents:**
- [Policy list and details](#policy-list-and-details)
  - [ACM Configuration](#acm-configuration)
  - [Cluster Configuration](#cluster-configuration)
  - [Cluster Health](#cluster-health)
  - [Cluster Maintenance](#cluster-maintenance)
  - [Cluster Validations](#cluster-validations)
  - [Gatekeeper](#gatekeeper)
  - [Operators](#operators)


[//]: # (Editor notes)
[//]: # (All policies should be listed alphabetical and where possible the table | should be aligned with the header row)

## ACM Configuration
  | Policy                                                                            | Description   |
  |--------                                                                           |-------------  |
  | [](../policies)                    |  |

## Cluster Configuration
  | Policy                                                                            | Description   |
  |--------                                                                           |-------------  |
  | [](../policies)                    |  |

## Cluster Health
  | Policy                                                                            | Description   |
  |--------                                                                           |-------------  |
  | [](../policies)                    |  |

## Cluster Maintenance
  | Policy                                                                            | Description   |
  |--------                                                                           |-------------  |
  | [](../policies)                    |  |

## Cluster Validations
  | Policy                                                                            | Description   |
  |--------                                                                           |-------------  |
  | [](../policies)                    |  |

## Gatekeeper
  | Policy                                                                            | Description   |
  |--------                                                                           |-------------  |
  | [](../policies)                    |  |

## Operators
  | Policy                                                                            | Description   |
  |--------                                                                           |-------------  |
  | [Advanced Cluster Management Operator](../policies/operators/acm/)                | Deploys ACM Operator and `MultiClusterHub` |
  | [Advanced Cluster Security Operator](../policies/operators/acs/)                  | Deploys ACS Operator and creates `Centeral` on the hub and `SecureCluster` on the managed clusters |
  | [Ansible Automation Platform Operator](../policies/operators/ansible-automation-platform/) | Deploys AAP and creates an full instance including AAP Gateway |
  | [Cert-Manager Operator](../policies/operators/cert-manager/)                      | Deploys cert-manager along with example `ClusterIssuer` using CA Cert |
  | [Developer Hub Operator](../policies/operators/developer-hub/)                    | Deploys Developer Hub and connects all managed clusters |
  | [Distributed Tracing (Tempo) Operator](../policies/operators/tempo/)              | Deploys Tempo Operator |
  | [Gatekeeper Operator](../policies/operators/gatekeeper/)                          | Deploys Gatekeeper Operator and configures `Gatekeeper` |
  | [OpenShift Cluster Logging Operator](../policies/operators/cluster-logging/)      | Deploys Cluster Logging Operator and configures `LokiStack`. |
  | [OpenShift Cluster Observability Operator](../policies/operators/)                | Deploys Cluster Observability Operator |
  | [OpenShift Data Foundation Operator](../policies/operators/data-foundation/)      | Deploys ODF and configures Object-Gateway storage |
  | [OpenShift GitOps Operator](../policies/operators/gitops/)                        | Deploys GitOps Operator and configures both cluster and namespace instances of `ArgoCD` |
  | [OpenShift Network Observability Operator](../policies/operators/network-observability/) | Deploys Network Observability Operator and configures `TempoStack` |
  | [OpenShift Pipelines Operator](../policies/operators/tekton/)                     | Deploys Pipeline Tekton Operator |
  | [OpenShift Service Mesh Operator](../policies/operators/servicemesh/)             | Deploys Service Mesh Operator and configures a cluster wide mesh |
  | [Red Hat Kiali Operator](../policies/operators/kiali/)                            | Deploys Kiali Operator |
  | [Red Hat Loki Operator](../policies/operators/loki/)                              | Deploys Loki Operator |
  | [Red Hat Open Telemetry Operator](../policies/operators/opentelemetry/)           | Deployed Open Telemetry Operator |
  | [Topology Aware Lifecycle Manager Operator](../policies/operators/talm/)          | Deploys TALM Operato |
  | [Workload Availability Operator](../policies/operators/workload-availability/)    | Deploys Workload Availabilty and includes multiple examples for configuring remediation |


[//]: # (Example Table layout)
[//]: # (  | Policy                                                                            | Description   |  )
[//]: # (  |--------                                                                           |-------------  |  )
