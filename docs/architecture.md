# Architecture

```mermaid
flowchart LR
  U[Users] --> LB[LoadBalancer Service]
  LB --> WP[WordPress Pod]
  WP --> MYSQLSVC[MySQL Service]
  MYSQLSVC --> DB[MySQL Pod]
  WP --> WPPVC[WordPress PVC]
  DB --> DBPVC[MySQL PVC]
