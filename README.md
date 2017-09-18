To generate a single yaml file, install https://github.com/whitlockjc/json-refs and run from the root directory of this project:

```sh
json-refs resolve docs/index.yaml --force --yaml > index.yaml
```

The resulting file can be loaded directly into swagger ui.
