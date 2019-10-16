# eslint-config-exivity

## installing

```
yarn add eslint-config-exivity --dev
```

## configurations

This package exports 3 configurations:

### `exivity/core`

This is the default configuration that applies to every Exivity JS project. It defines the standard eslint rules as well as defining typescript rules and import rules.

```js
{
  extends: ["exivity/core"]
}
```

For this config to work properly it requires these peer dependencies:

```
"eslint": ">= 5.6.0",
"eslint-plugin-import": ">= 2.18.2",
"@typescript-eslint/eslint-plugin": ">= 2.3.0",
"@typescript-eslint/parser": ">= 1.11.0",
```

### `exivity/testing`

This configuration defines all the rules for how Exivities testing suites should look.
 
 ```js
{
  extends: ["exivity/testing"]
}
```

For this config to work properly it requires these peer dependencies:

```
"eslint": ">= 5.6.0",
"eslint-plugin-jest": ">= 22.17.0",
"eslint-plugin-jest-formatting": ">= 1.1.0"
```

### `exivity/react`

This configuration defines all the React specific rules as well as rules that have to do with jsx.

 ```js
{
  extends: ["exivity/react"]
}
```

For this config to work properly it requires these peer dependencies:

```
"eslint": ">= 5.6.0",
"eslint-plugin-jsx-a11y": ">= 6.0.3",
"eslint-plugin-react": ">= 7.14.3",
"eslint-plugin-react-hooks": ">= 2.0.1"
```
