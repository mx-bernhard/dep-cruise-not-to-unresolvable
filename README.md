# To reproduce

```sh
yarn
yarn cruise
```

Error reported, but package is available:

```log
$ dependency-cruise packages

  error not-to-unresolvable: packages/foo-package/src/foo.ts → @chevrotain/types

✘ 1 dependency violations (1 errors, 0 warnings). 2 modules, 1 dependencies cruised.
```
