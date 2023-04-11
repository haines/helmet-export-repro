The tsconfig.json used here was generated with `npx tsc --init` (using TypeScript 5.0.4).
The only customization is to remove `skipLibCheck`.

```console
$ npx tsc --noEmit
node_modules/helmet/index.d.ts:120:1 - error TS2309: An export assignment cannot be used in a module with other exported elements.

120 export = helmet
    ~~~~~~~~~~~~~~~


Found 1 error in node_modules/helmet/index.d.ts:120
```
