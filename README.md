# Infrastructure
Architecture Summary
```shell
Spring Boot
 ├── ConfigMap → application.yaml
 ├── Secret → DB password
 ├── Deployment → container
 ├── Service → networking
 ├── HPA → autoscaling
 └── Kustomize / Helm → env management
```
