# Personal testing of Github actions

## Publish Helm repos to github pages

The github actions workflows lints and tests the charts on a pull request and packages and publishes the chart to Github pages.

You can then use the chart with:

```shell
# add the repo
helm repo add knappek https://knappek.github.io/github-actions-getting-started
# see all charts of the repo
helm search repo knappek
# install the chart
helm install knappek/hello-world
```
