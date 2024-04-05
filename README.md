# HELM Charts

## Advantages of HELM

- Helm allows us to bundle YAML files to be deployed in Kubernetes.

- It gives a organized and neat structure to store you YAML files.

- It allows us to pass variables to YAML files

## Commands

Create a heml chart folder structure from template

```bash
helm create <helm-char-name>
```

```bash
  ├── charts
  ├── Chart.yaml
  ├── templates
  │   ├── deployment.yaml
  │   ├── _helpers.tpl
  │   ├── hpa.yaml
  │   ├── ingress.yaml
  │   ├── NOTES.txt
  │   ├── serviceaccount.yaml
  │   ├── service.yaml
  │   └── tests
  │       └── test-connection.yaml
  └── values.yaml
```
