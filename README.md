# Ahmed Badawy

**Cloud and Platform Architect** · AWS, Kubernetes and AI infrastructure ·

I have 13+ years of experience designing and operating AWS and hybrid infrastructure. I combine architecture ownership and technical leadership with hands-on Kubernetes, Terraform, CI/CD and observability.

#### GitHub Statistics

![](https://github-readme-streak-stats-eight.vercel.app/?user=ahmedbadawy4&theme=dark&hide_border=false&v=2)  
![](https://github-readme-stats.shion.dev/api/top-langs/?username=ahmedbadawy4&theme=dark&hide_border=false&layout=compact)

#### Trophies

![](https://github-profile-trophies.vercel.app/?username=ahmedbadawy4&theme=dark&column=7&margin-w=15&margin-h=15)


[LinkedIn](https://www.linkedin.com/in/theahmedbadawy)

## What I work with

| Area | Tools and practices |
|---|---|
| Cloud platforms | AWS, Azure, GCP and hybrid infrastructure |
| Containers | Kubernetes, Docker, Helm |
| Infrastructure as code | Terraform, Terragrunt, AWS CDK, Pulumi, Ansible |
| CI/CD | GitHub Actions, Jenkins, GitLab CI/CD, GitOps, blue-green and canary deployments |
| Observability | Datadog, Prometheus, Grafana and Alloy, ELK stack, OpenTelemetry, service level indicators and objectives (SLI and SLO) |
| AI infrastructure | Bedrock and OpenAI APIs through Envoy AI Gateway, Model Context Protocol (MCP) and agent tooling, with tool permissions, human approvals, audit trails and usage budgets |
| Automation | Python, Bash, AWS Lambda |

## Public projects

Most of my professional work was done inside company environments, so it is not public. These repositories are small reference setups and prototypes that show how I build and review infrastructure. None of them is a production system.

| Project | What it is | What it shows |
|---|---|---|
| [llm-renewal-desk-agent](https://github.com/ahmedbadawy4/llm-renewal-desk-agent) | Prototype LLM decision-support agent for SaaS vendor renewals. Python service with citation checks and guardrails, Prometheus metrics, OpenTelemetry traces and Grafana dashboards, packaged with a Helm chart. | AI controls, observability, Helm, CI |
| [cloud-native-automation-architecture](https://github.com/ahmedbadawy4/cloud-native-automation-architecture) | Argo CD GitOps setup on Kubernetes. App-of-apps pattern, dev and prod environments separated by namespaces and Helm values, Git-driven promotion, GitHub Actions for build and release. | GitOps, Helm, CI/CD |
| [aws-terraform-infrastructure](https://github.com/ahmedbadawy4/aws-terraform-infrastructure) | Terraform modules for an Amazon EKS cluster and a VPC, deployed with Terragrunt to two environments that share one state backend. Includes an Atlantis server (Terraform and Ansible) and pre-commit checks in GitHub Actions. | Infrastructure as code, AWS, EKS |
| [aws-terraform-webapp](https://github.com/ahmedbadawy4/aws-terraform-webapp) | Terraform setup for one EC2 web server and one PostgreSQL database on Amazon RDS in a new VPC. RDS creates the database password in AWS Secrets Manager, a KMS key encrypts it and the storage, and the server's IAM role can read only that secret. GitHub Actions run tflint, Checkov and pre-commit. | Infrastructure as code, AWS, secrets handling |
| [gke-cloudsql-terraform](https://github.com/ahmedbadawy4/gke-cloudsql-terraform) | Terraform for a VPC, a GKE cluster, Cloud SQL for PostgreSQL with a private address and an Artifact Registry repository, in development and production. Argo CD syncs Kustomize overlays, and GitHub Actions publish the image through Workload Identity Federation instead of stored keys. | Infrastructure as code, GCP, GitOps |
| [helm-rest-api](https://github.com/ahmedbadawy4/helm-rest-api) | Helm chart for a stateless REST API with dev and prod values, a Prometheus ServiceMonitor, and a tag-based release flow that publishes the image to GitHub Container Registry. | Helm, release automation |
| [k8s-observability](https://github.com/ahmedbadawy4/k8s-observability) | Observability stack for a local kind cluster. Applications send OpenTelemetry data to Grafana Alloy, which writes metrics to Prometheus and traces to Tempo, with Grafana on top. A Helm chart adds multi-window, multi-burn-rate SLO alerts. CI checks the rules with promtool and the manifests with kubeconform. | Observability, SLO alerting, OpenTelemetry |
| [simple-go](https://github.com/ahmedbadawy4/simple-go) | Go service that uses only the standard library, with unit tests, health and Prometheus endpoints, a small container image, a Helm chart and an Argo CD Application. GitHub Actions run the tests and chart checks, and push the image to GitHub Container Registry on version tags. | Go, Helm, GitOps, CI/CD |
| [wordpress-helm-chart](https://github.com/ahmedbadawy4/wordpress-helm-chart) | Helm chart for WordPress with its own MySQL database: dedicated database user, probes, optional Ingress and a NetworkPolicy. GitHub Actions install it on a kind cluster, run the Helm test and publish the chart to GitHub Container Registry on version tags. | Helm, Kubernetes, release automation |
