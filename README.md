[typescript-eslint 7.1.0 released a -type-checked-only set of configs](https://github.com/typescript-eslint/typescript-eslint/releases/tag/v7.1.0). However, they seem to be missng in practice!

This PR is a reproduction of the issue:

Flat config:

```shell
cd flat-config
pnpm install
pnpm eslint .
```

Legacy config:

```shell
cd legacy-config
pnpm install
pnpm eslint .
```

An error should show up in both cases.
