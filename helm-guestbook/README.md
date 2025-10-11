# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout 171c4ae07c080285fe0068c8dbac6c6f346b5bb3
helm template . --name-template my-app --include-crds
```
