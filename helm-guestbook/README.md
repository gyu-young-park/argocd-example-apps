# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout ab80d2f6f4e44f49303a4ccd7a8a339eb11a4c56
helm template . --name-template my-app --include-crds
```
