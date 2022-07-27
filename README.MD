Demonstrating that when building locally (pnpm build) then deploying with `--prebuilt` it somehow messes up rewrites so that only the last rewrite works once deployed.

Take note of rewrites in `vercel.json`

```sh
pnpm build
vercel --prebuilt
```