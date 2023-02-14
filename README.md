# se-helm-charts
SE Helm Charts

https://semantic-evolution.github.io/se-helm-charts/index.yaml

```
helm repo add semantic-evolution https://semantic-evolution.github.io/se-helm-charts/
```


1) Create helm package `helm package PATH_WITH_SOURCES`
3) Add generated .tgz file to this repository. 
2) Commit and push to main branch. Github action pipeline will re-index packages.