# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout ac1db65e0902930ff656ea10f536947af333c44c
helm template . --name-template my-app --include-crds
```
