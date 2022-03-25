# GB Flarum Prettier Config

Glowing Blue's configuration for the Prettier code formatter (for Flarum Projects).

For more info about shared Prettier configurations,
[check out the Prettier documentation](https://prettier.io/docs/en/configuration.html#sharing-configurations).

## Usage

1. Install `@glowingblue/prettier-config` as a dev dependency:

```
yarn add -D @glowingblue/prettier-config
```

1. Add the `prettier` key to your `package.json`:

```jsonc
// package.json
{
	"name": "my-cool-package",
	"version": "1.0.0",
	"prettier": "@glowingblue/prettier-config"
	// ...
}
```