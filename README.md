# eslint-plugin-valk-plugin

plugin for production project

## Installation

You'll first need to install [ESLint](https://eslint.org/):

```sh
npm i eslint --save-dev
```

Next, install `eslint-plugin-valk-plugin`:

```sh
npm install eslint-plugin-valk-plugin --save-dev
```

## Usage

Add `valk-plugin` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "valk-plugin"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "valk-plugin/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here


