# To reproduce

```sh
yarn
yarn cruise
```

Error reported, but package is available:

```log
$ dependency-cruise src

  error not-to-unresolvable: src/foo.ts → @chevrotain/types

✘ 1 dependency violations (1 errors, 0 warnings). 2 modules, 1 dependencies cruised.
```
