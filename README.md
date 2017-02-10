# eslint-config-dreidev
ESLint shareable config for the Dreidev JavaScript style guide

## Installation

```
$ npm install --save-dev eslint eslint-config-dreidev
```

## Usage

Once the `eslint-config-dreidev` package is installed, you can use it by specifying `dreidev` in the [`extends`](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) section of your [ESLint configuration](http://eslint.org/docs/user-guide/configuring).

```js
{
  "extends": "dreidev",
  "rules": {
    // Additional, per-project rules...
  }
}
```

#### Credit
- This repo is hugely inspired by [eslint-config-google](https://github.com/google/eslint-config-google) customizing the rules to our preferences.
- The Dreidev javascript style guide closely but not strictly follows [airbnb/javascript](https://github.com/airbnb/javascript)
