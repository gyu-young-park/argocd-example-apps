# Manifest Hydration???????? hello
To hydrate the manifests gyu!!! repository, run the following commands:

Go!! Argocd!!! https://github.com/gyu-young-park/argocd-example-apps.git
```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout 25a659434e0b0f381f10bea8cf73de9eb21c8802
helm template . --name-template my-app --include-crds
```

