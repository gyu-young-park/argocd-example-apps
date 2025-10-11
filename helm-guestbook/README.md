# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout 54f013c2cde0dd25b49dd7242950182645c1891f
helm template . --name-template my-app --include-crds
```
