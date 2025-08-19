# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout 52c4362f27a230a782dca7e4c96e79d7d6001dda
helm template . --name-template my-app --include-crds
```
