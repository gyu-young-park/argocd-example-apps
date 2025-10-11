# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout 94ab1eff8e08647ab2473c1996fcef375914a3d7
helm template . --name-template my-app --include-crds
```
