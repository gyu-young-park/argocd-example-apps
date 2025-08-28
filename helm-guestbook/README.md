# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout 641c8fd405502fb652238308b0e38480cff5deae
helm template . --name-template my-app --include-crds
```
