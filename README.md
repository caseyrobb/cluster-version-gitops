# cluster-version-gitops

Demo repo to manage OpenShift cluster upgrades with GitOps

```
.
├── base
│  ├── clusterversion.yaml
│  └── kustomization.yaml
├── clusterversion-application.yaml
├── overlays
│  ├── 4.11.36
│  │  └── kustomization.yaml
│  ├── 4.11.40
│  │  └── kustomization.yaml
│  └── 4.11.44
│     └── kustomization.yaml
└── README.md
```
