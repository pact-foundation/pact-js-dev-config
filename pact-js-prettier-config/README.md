Pact-JS Developer Prettier config
---------------------------------

This is the prettier config for pact-js projects, used to keep consistency across the projects.
Please use these options to format any new pact projects.

It's hosted at
[https://github.com/pact-foundation/pact-js-dev-config](https://github.com/pact-foundation/pact-js-dev-config),
which contains shared config for javascript (and related) pact projects.

It's essentially default prettier settings, with single quotes added.
See this excellent documentation page on prettier's [option
philosophy](https://prettier.io/docs/en/option-philosophy.html).

### How do I use it?

Add this to your package.json:

```
  "prettier": "@pact-foundation/pact-js-prettier-config"
```

Or if you use `.prettierrc.json`: 

```
"@pact-foundation/pact-js-prettier-config"
```

See [here](https://prettier.io/docs/en/configuration.html#sharing-configurations) for details.

### Can I use this to format something that isn't a pact project?

I mean, sure, if you like. We're not the boss of you.

