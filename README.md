# deno-json-rewrite-relative-path

```
deno run src/mod.ts
```

Error

```
Unsupported compiler options in "deno-json-rewrite-relative-path/deno.json".
  The following options were ignored:
    baseUrl, paths
error: Relative import path "~/greet.ts" not prefixed with / or ./ or ../
    at deno-json-rewrite-relative-path/src/mod.ts:1:19
```