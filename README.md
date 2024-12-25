sample 

<your-repository>
│
├── argocd/                       # Store ArgoCD templates and values here
│   ├── argocd-app-template.yaml   # The ArgoCD Application template (Helm template)
│   └── values.yaml                # Default values.yaml for the environment
├── charts/                        # Store Helm charts here
│   ├── cnoe-helm/                 # Example Helm chart directory
│   │   ├── Chart.yaml             # Chart metadata (name, version, dependencies)
│   │   ├── values.yaml            # Chart-specific values file
│   │   ├── templates/             # Directory containing Kubernetes manifest templates
│   │   │   ├── deployment.yaml   # Deployment template
│   │   │   ├── service.yaml      # Service template
│   │   │   └── ingress.yaml      # Ingress template (optional)
│   │   └── charts/               # Subcharts (optional)
│   └── README.md                  # Documentation for the Helm chart
└── README.md                      # Documentation for setting up ArgoCD
