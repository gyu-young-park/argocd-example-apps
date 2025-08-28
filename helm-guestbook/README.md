# Manifest Hydration???????? hello
To hydrate the manifests gyu!!! repository, run the following commands:

Go!! Argocd!!! https://github.com/gyu-young-park/argocd-example-apps.git
```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout bc9d9d8e401fbe933307a58af8fbce3e94a28853
helm template . --name-template my-app --include-crds
```

