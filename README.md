<div align="center">
    <h1>Helm charts for Kubernetes</h1>
    <a href="https://github.com/profumo-di-pizza/charts/actions/workflows/chart-releaser.yml"><img alt="Release Charts" src="https://img.shields.io/github/actions/workflow/status/profumo-di-pizza/charts/chart-releaser.yml?branch=main&label=Release%20charts&logo=github"></a>
    <a href="https://opensource.org/licenses/Apache-2.0"><img alt="profumo-di-pizza" src="https://img.shields.io/badge/License-Apache%202.0-blue.svg"></a>
</div>

Applications developed by [@profumo-di-pizza](https://github.com/profumo-di-pizza) ready to launch on Kubernetes using [Helm](https://helm.sh).

⚠️ Prerequisites
- Helm 3.1.0+

## Usage

```bash
helm repo add profumo-di-pizza https://profumo-di-pizza.github.io/charts
helm search repo profumo-di-pizza
helm install my-release profumo-di-pizza/<chart>
```
