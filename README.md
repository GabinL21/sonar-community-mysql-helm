Answer to this Community thread: https://community.sonarsource.com/t/github-action-kubernetes-helm-scan-no-issues-found/129992/4

The MySQL Helm chart is from Bitnami: https://artifacthub.io/packages/helm/bitnami/mysql

The `output.yaml` file is the evaluated template, generated with the following command:

```shell
 helm template my-release mysql --values mysql/values.yaml > output.yaml
```
