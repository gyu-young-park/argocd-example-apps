# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout 152467039d3bb5ff75ff0ddb0865e90d071fc63e
helm template . --name-template my-app --include-crds
```
