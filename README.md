# Hybrid Connectivity and Azure Arc

This repository documents enterprise hybrid connectivity, Azure Arc enablement, and governance patterns for unified operations across cloud and on-premise estates.

```mermaid
flowchart LR
    A[On-prem] --> B[ExpressRoute / VPN]
    B --> C[Azure]
    D[Arc-enabled Servers] --> E[Unified Operations]
    F[Arc-enabled Kubernetes] --> E
```
