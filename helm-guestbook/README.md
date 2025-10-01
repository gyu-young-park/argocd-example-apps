# Manifest Hydration
Hello world! This is README template! sha: f4e28fefc44f4b80e57a2e6c8baf5f606e55c6c2
Repo: https://github.com/gyu-young-park/argocd-example-apps.git

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout f4e28fefc44f4b80e57a2e6c8baf5f606e55c6c2
helm template . --name-template my-app --include-crds
```

