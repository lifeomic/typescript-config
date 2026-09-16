# typescript-config
Export the Typescript Configuration

[The extends property](https://www.typescriptlang.org/tsconfig#extends) "... path may use Node.js style resolution"

Add `@lifeomic/typescript-config` as a dev dependency, put the following in the `tsconfig.json` file

```JSON
{
  "extends": "@lifeomic/typescript-config",
  ...
}
```

Requirements:
* TypeScript `>=5.0.0` (TypeScript 5, 6, and native TypeScript 7)
* Node.js 18+

Latest Breaking changes:
* `module` and `moduleResolution` are `nodenext`. TypeScript 6 deprecated `moduleResolution: node` (`node10`); TypeScript 7 removes it. Consumers can still override in their own `tsconfig.json`.
* Builds to ES2022 output for Node.js 18+
