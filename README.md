# Some Helm Charts

- simple-spring-boot : a standalone spring boot api - for `/cheese`
- tutorial-crud-api : a mongodb and nodejs example api for `/api/tutorials`

Publish a helm chart to a helm repo:

```
helm repo add purplesky-charts https://nexus-nexus.apps.ocp1.purplesky.cloud/repository/purplesky-charts/

helm package ./simple-spring-boot
mkdir purplesky-charts
mv sb-app-0.1.0.tgz purplesky-charts/
```
login to nexus and upload.

TODO: tool to auto upload helm charts?

