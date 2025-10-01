# Manifest Hydration
Hello world! This is README template!

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout a5e1e9704c1b3a2694655186599e87800dc90011
helm template . --name-template my-app --include-crds
```

