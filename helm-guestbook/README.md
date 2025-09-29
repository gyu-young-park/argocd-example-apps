# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout 6b680609007582ad443120dded009029fa8dc92f
helm template . --name-template my-app --include-crds
```
