# GitHub Action to NPM Publish

![https://github.com/zmicro-design/action-npm-publish](https://img.shields.io/github/v/release/zmicro-design/action-npm-publish)
![https://github.com/zmicro-design/action-npm-publish](https://github.com/zmicro-design/action-npm-publish/workflows//Publish/badge.svg)

### Usage

| option | required | description |
| ------ | -------- | ----------- |
｜ registry | false | npm auth token |
| token | true | npm registry |
| always-auth | false | set always-auth |

### Example

```yml
name: CI

on: [push]

jobs:
  build:
    name: Test
    runs-on: ubuntu-latest
    steps:
      - name: NPM Publish
        uses: zmicro-design/action-npm-publish@v1
```

### License

[MIT](./LICENSE)
