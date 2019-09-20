# eslint-config

This package has 3 configurations. 

default config:

This is the default configuration that applies to every Exivity JS project. It defines the standard eslint rules as defining typescript rules and import rules.

```js
{
  extensions: ['exivity']
}
```

`testing`:

 This configuration defines all the rules for how Exivities testing suites should look.
 
 ```js
{
  extensions: ['exivity/testing']
}
```

`react`:

This configuration defines all the react specific rules as well as rules that have to do with jsx.

 ```js
{
  extensions: ['exivity/react']
}
```
