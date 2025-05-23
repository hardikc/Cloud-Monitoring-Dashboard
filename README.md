# Cloud-Monitoring-Dashboard
Real-time monitoring dashboard for AWS using Grafana and CloudWatch
cloud-monitoring-dashboard/
├── infrastructure/
│   ├── main.tf            # Terraform config for AWS
│   └── variables.tf       # AWS credentials/region
├── grafana-config/
│   ├── dashboard.json     # Exported Grafana dashboard
│   └── aws-datasource.yaml # CloudWatch data source
├── scripts/
│   ├── deploy.sh          # Setup Grafana + CloudWatch
│   └── alerts.sh          # Configure alerts
└── README.md              # Setup instructions
