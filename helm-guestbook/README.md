# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout 5942c4daa93e880b036ddb789980822cc48870aa
helm template . --name-template my-app --include-crds
```
