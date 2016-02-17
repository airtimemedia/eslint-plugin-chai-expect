# eslint-plugin-chai-expect

[![Build Status](https://img.shields.io/travis/Turbo87/eslint-plugin-chai-expect/master.svg)](https://travis-ci.org/Turbo87/eslint-plugin-chai-expect)

ESLint plugin that checks for common chai.js expect() mistakes


# Installation

```
npm install eslint-plugin-chai-expect
```


# Configuration

Add a `plugins` section and specify `chai-expect` as a plugin:

```json
{
  "plugins": [
    "chai-expect"
  ]
}
```

Enable the rules that you would like to use:

```json
{
  "rules": {
    "chai-expect/missing-assertion": 2
  }
}
```


# Rules

- `missing-assertion` - Prevent calling `expect(...)` without an assertion like `.to.be.ok`


# License

eslint-plugin-chai-expect is licensed under the [MIT License](http://www.opensource.org/licenses/mit-license.php).