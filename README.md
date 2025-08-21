# Helm Chart

Helm chart repository provided by imkhkim

## Usage

### Add this repository to your Helm
```bash
helm repo add imkhkim-helm-repo https://imkhkim.github.io/helm-repo/
helm repo update
```

### List repositories
```bash
helm repo list
```

### Search for charts
```bash
# Search all charts in this repository
helm search repo imkhkim-helm-repo

# Search for specific chart in all repositories
helm search repo <chart-name>

# Search for specific chart in this repository
helm search repo imkhkim-helm-repo/<chart-name>
```

### Install a chart
```bash
helm install <release-name> imkhkim-helm-repo/<chart-name>
```

### Remove this repository from your Helm
```bash
helm repo remove imkhkim-helm-repo
```
