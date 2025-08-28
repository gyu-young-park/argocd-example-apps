# Manifest Hydration???????? hello
To hydrate the manifests gyu!!! repository, run the following commands:

Dynamic reload!!  https://github.com/gyu-young-park/argocd-example-apps.git
```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout 355124faf7da3ea56824f752a82e6904ea1c950b
helm template . --name-template my-app --include-crds
```

