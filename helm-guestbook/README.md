# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout 5bb10e6269b9a41562d3080632809d5bab64739e
helm template . --name-template my-app --include-crds
```
