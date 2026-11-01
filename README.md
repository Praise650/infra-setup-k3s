### Current file structure
infra-setup-k3s/
├── platform/
│   ├── apps/
│   ├── environments/
│   │   ├── dev/
│   │   │   ├── podinfo-stage-1.yaml
│   │   │   ├── podinfo-stage-2.yaml
│   │   │   ├── saleor-api-3a.yaml
│   │   │   ├── saleor-api-3b.yaml
│   │   │   ├── saleor-dashboard.yaml
│   │   │   ├── saleor-data.yaml
│   │   │   ├── saleor-ingress.yaml
│   │   │   ├── saleor-media.yaml
│   │   │   ├── saleor-migrate-job.yaml
│   │   │   ├── saleor-populatedb-job.yaml
│   │   │   ├── saleor-storefront.yaml
│   │   │   └── saleor-worker.yaml
│   │   ├── prod/
│   │   └── staging/
│   └── infrastucture/
├── .env
├── .gitignore
├── inventory.ini
├── kubeconfig
├── README.md
├── site-old.yml
└── site.yml

platform/
platform/apps/
platform/environments/
platform/environments/dev/
platform/environments/prod/
platform/environments/staging/
platform/environments/dev/podinfo-stage-1.yaml
platform/environments/dev/podinfo-stage-2.yaml
platform/environments/dev/saleor-api-3a.yaml
platform/environments/dev/saleor-api-3b.yaml
platform/environments/dev/saleor-dashboard.yaml
platform/environments/dev/saleor-data.yaml
platform/environments/dev/saleor-ingress.yaml
platform/environments/dev/saleor-media.yaml
platform/environments/dev/saleor-migrate-job.yaml
platform/environments/dev/saleor-populatedb-job.yaml
platform/environments/dev/saleor-storefront.yaml
platform/environments/dev/saleor-worker.yaml
platform/infrastucture/
.env
.gitignore
inventory.ini
kubeconfig
README.md
site-old.yml
site.yml

### Suggested file structure
k3s-platform/
├── apps/
│   ├── frontend/
│   ├── backend/
│   └── ecommerce/
├── environments/
│   ├── dev/
│   ├── staging/
│   └── prod/
├── infrastructure/
│   ├── ingress/
│   ├── monitoring/
│   └── storage/
└── .github/
    └── workflows/