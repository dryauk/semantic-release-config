# @dryauk/semantic-release-config

[**semantic-release**](https://github.com/semantic-release/semantic-release) shareable config.

## Plugins

This shareable configuration use the following plugins:

- [`@semantic-release/commit-analyzer`](https://github.com/semantic-release/commit-analyzer)
- [`@semantic-release/release-notes-generator`](https://github.com/semantic-release/release-notes-generator)
- [`@semantic-release/npm`](https://github.com/semantic-release/npm)
- [`@semantic-release/github`](https://github.com/semantic-release/gitlab)
- [`@semantic-release/changelog`](https://github.com/seamntic-release/changelog)
- [`@semantic-release/git`](https://github.com/seamntic-release/git)

## Install

```bash
yarn add -D semantic-release @dryauk/semantic-release-config
```

## Usage

The shareable config can be configured in the [**semantic-release** configuration file](https://github.com/semantic-release/semantic-release/blob/master/docs/usage/configuration.md#configuration):

```json
{
  "extends": "@dryauk/semantic-release-config"
}
```

## Configuration

See each [plugin](#plugins) documentation for required installation and configuration steps.
