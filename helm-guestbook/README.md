# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout 1dd782857e1f0d6d3a5fc18ce206de53f92be396
helm template . --name-template my-app --include-crds
```
