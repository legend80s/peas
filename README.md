# Peas

<div align="center">
  <img src="https://koboyo.com/icons/svg/pea-pod.svg" width="15%" />
</div>

> A pseudo mono repo for util packages only run in Node.js such as walking-log, walking-file-logger etc.

It is just a shell—like a pea pod—for shared `devDependencies` (TypeScript, Biome, [npm-shipwright](https://www.npmjs.com/package/npm-shipwright), etc.) and shared files (.gitignore, etc.) across the packages in `./packages/**`.

> [!CAUTION]
>
> - This repo should not be published. Only `./packages/**` can be published.

## Publish

Should publish all packages in `./packages/**` with the same command in the root directory:

```bash
# root
pnpm release
```
