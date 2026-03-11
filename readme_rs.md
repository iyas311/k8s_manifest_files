ReplicaSet
│
├─ apiVersion
├─ kind
├─ metadata
│   ├─ name
│   ├─ namespace
│   └─ labels
│
└─ spec
    ├─ replicas
    ├─ selector
    │    └─ matchLabels
    │
    └─ template
         ├─ metadata
         │    └─ labels
         │
         └─ spec
              └─ containers
                   └─ container
                        ├─ name
                        ├─ image
                        └─ ports
                             └─ containerPort