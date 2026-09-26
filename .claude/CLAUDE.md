# Repo facts for Claude

This is an Argo CD GitOps repo managed with `argocd-gitops-plugin`. Read the
plugin skill `argocd-repo-conventions` before generating or editing any file here.

- GitOps repo URL: https://github.com/OmalCooray/argocd-plugin-livetest
- Default branch: master
- Argo CD namespace: argocd
- Environments: live
- Destination cluster for live: https://kubernetes.default.svc

## Catalog inventory

_(Updated by `/argocd-add-chart`.)_

| App | Upstream chart | Version | Repo |
|-----|----------------|---------|------|
| podinfo | podinfo | 6.15.0 | https://stefanprodan.github.io/podinfo |
| prometheus-operator-crds | prometheus-operator-crds | 32.0.1 | https://prometheus-community.github.io/helm-charts |
| metrics-server | metrics-server | 3.14.0 | https://kubernetes-sigs.github.io/metrics-server/ |

## Deployment matrix

_(Updated by `/argocd-deploy`.)_

| App | live |
|-----|----------------|
| podinfo | yes |
| prometheus-operator-crds | yes |
| metrics-server | yes |
