# Manifest Hydration
Hello world! This is README template! sha: cdd931dc1443c6c35ae7551b425b4fa426e69562
Repo: https://github.com/gyu-young-park/argocd-example-apps.git

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout cdd931dc1443c6c35ae7551b425b4fa426e69562
helm template . --name-template my-app --include-crds
```

