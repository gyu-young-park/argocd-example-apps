# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout 200372652c07de5555534f38c6495c8e58750d67
helm template . --name-template my-app --include-crds
```
