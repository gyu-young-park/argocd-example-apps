# Manifest Hydration
Hello world! This is README template!

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/gyu-young-park/argocd-example-apps.git
# cd into the cloned directory
git checkout b27b848a749e94875f28de88d489dad51f6de291
helm template . --name-template my-app --include-crds
```

