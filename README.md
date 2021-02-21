# `tit4tatt` all the things [![npm version][npm-image]][npm-url]

> This is the prodigal twin brother of the
  [`tatt` package](https://www.npmjs.com/package/tatt).
  It adds support for *path aliases* and *bare imports*,
  as is typically required in CommonJS build environments by
  antiquated frameworks that depend on source code transformation.

## Usage

### Installation

```bash
npm install tit4tatt
```

### Configuration

Add aliases that match your project's bundler in `package.json`:

```json
{
  "_moduleAliases": {
    "~": "."
  }
}
```

Note: `module-alias` is only registered in the `tit4tatt` executable.
The installation itself has no side effects on the
package resolution of your bundler.

## Next steps

From here on, refer to the documentation of the
[`tatt` package](https://www.npmjs.com/package/tatt).
The only differences are that both the *bare import* and the
executable name are `tit4tatt` instead of `tatt`.

## License

GNU Affero General Public License

SPDX-License-Identifier: `AGPL-3.0-or-later`

[npm-image]: https://img.shields.io/npm/v/tit4tatt.svg?style=flat-square
[npm-url]:   https://www.npmjs.com/package/tit4tatt
