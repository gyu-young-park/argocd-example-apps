# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout a543c86356d19f7696596d17876ea017c224f76a
helm template . --name-template my-app --include-crds
```
