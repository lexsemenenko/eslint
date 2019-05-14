# ESLint Configuration

My ESlint Configuration that I use in my projects using Airbnb as base settings.

Install ESLint Locally

```
$ npm i eslint -D
```

Create Basic Configuration File `.eslintrc`

```
{
  "extends": "eslint:recommended",
  "parserOptions": {
    "ecmaVersion": 2018
  },
  "env": {
    "node": true,
    "browser": true,
    "es6": true,
    "jquery": true
  }
}
```

## Editor

I use VSCode, so I install ESLint package for it.

- Just install it, and it will work of the existing `.eslintrc` configuration.
-  It will use local eslint package and fall back to global if the prior is not available.
-  You should see the same exact errors from the terminal in you editor.


## Airbnb Notes

Package for JavaScript:
`eslint-config-airbnb-base`

Package for React:
`eslint-config-airbnb`