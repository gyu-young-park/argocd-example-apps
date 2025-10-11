# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout 4de53f3650cac7bf95b80ca378d0249061d97c57
helm template . --name-template my-app --include-crds
```
