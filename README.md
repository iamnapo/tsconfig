# tsconfig

> TypeScript shareable config for [iamnapo](https://iamnapo.me)’s coding style

[![npm](https://badges.iamnapo.me/npm/@iamnapo/tsconfig)](https://www.npmjs.com/package/@iamnapo/tsconfig) [![style](https://badges.iamnapo.me/style)](https://iamnapo.me)

## Install

```console
npm i @iamnapo/tsconfig -D
```

Then, add this to your `tsconfig.json`:

```json
{
	"extends": "@iamnapo/tsconfig"
}
```

> This config requires TypeScript >=6.

TypeScript no longer includes `@types/node` automatically. If your project uses Node.js APIs, install `@types/node` and add it to `types`:

```json
{
	"extends": "@iamnapo/tsconfig",
	"compilerOptions": {
		"types": ["node"]
	}
}
```
