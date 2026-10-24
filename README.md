# @x12i/agentra-core usage example

Core utilities and domain logic for Agentra.

This consuming application demonstrates **validate incoming json and report contract errors** using the published npm package, pinned to `0.1.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- Use shared Agentra domain utilities in a consumer.
- Validate a supported event contract before composing a larger analytics operation.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/agentra-core)
- [Implementation monorepo](https://github.com/x12i/agentra)
- [Reviewed package source](https://github.com/x12i/agentra/tree/772e50e64925e6359e42172d4dcf11d4aa795763/packages/core)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
