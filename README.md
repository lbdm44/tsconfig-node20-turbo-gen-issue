# tsconfig-node20-turbo-gen-issue

This repo is a simple reproduction of an issue in a much larger repo.

## Error

```sh
❯ yarn turbo gen

>>> Modify "tsconfig-node20-turbo-gen-issue" using custom generators


>>> Unexpected error. Please report it as a bug:
error TS6053: File '@tsconfig/node20/tsconfig.json' not found.
```

## Steps to Reproduce

1. Checkout this repo.
2. `yarn install`
3. `yarn turbo gen` or `yarn turbo gen run`

## Notes

- If we do not have `typescript` as a dependency, this issue does not occur.
