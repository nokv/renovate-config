# @nokv/renovate-config

My [shareable config](https://renovatebot.com/docs/config-presets/) for [Renovate](https://renovatebot.com)

[![npm version][npm-image]][npm-url]
[![build status][ci-image]][ci-url]
![License][license]

## Usage

Enable Renovate in your repo and just `extends` in `renovate.json`.

```json
{
    "extends": ["github>nokv/renovate-config"]
}
```

Note: You don't have to do `npm i -D @nokv/renovate-config`.
Renovate fetches it from this GitHub repo automatically.

## LICENSE

MIT License

[npm-image]: https://img.shields.io/npm/v/@nokl/renovate-config.svg
[npm-url]: https://npmjs.org/package/@nokl/renovate-config
[npm-downloads-image]: https://img.shields.io/npm/dm/@nokl/renovate-config.svg
[ci-image]: https://github.com/nokv/renovate-config/workflows/ci/badge.svg
[ci-url]: https://github.com/nokv/renovate-config/actions?query=workflow%3Aci
[node-version]: https://img.shields.io/badge/Node.js%20support-v16-brightgreen.svg
[license]: https://img.shields.io/npm/l/@nokl/renovate-config.svg
