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

Latest Breaking changes:
* Builds to ES2022 output for nodejs 18
