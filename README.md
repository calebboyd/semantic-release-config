## Install

```shell
npm i -D semantic-release @calebboyd/semantic-release-config
```
## Configure

```json
{
  "extends": "@calebboyd/semantic-release-config",
  "branch": "master"
}
```

A [semantic-release](https://github.com/semantic-release/semantic-release) shareable config to publish npm packages.



## Plugins

This [shareable configuration](https://github.com/jedmao/semantic-release-npm-github-config/blob/master/.releaserc.json) uses the following plugins:

- [`@semantic-release/commit-analyzer`](https://github.com/semantic-release/commit-analyzer)
- [`@semantic-release/release-notes-generator`](https://github.com/semantic-release/release-notes-generator)
- [`@semantic-release/npm`](https://github.com/semantic-release/npm)
- [`@semantic-release/github`](https://github.com/semantic-release/github)
- [`@semantic-release/git`](https://github.com/semantic-release/git)

