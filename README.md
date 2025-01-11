To fetch submodules:

```shell
git submodule update --init --recursive
```

To update submodules (after commiting to them):

```shell
git push --recurse-submodules=on-demand
```
