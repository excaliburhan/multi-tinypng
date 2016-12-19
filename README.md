# MultiPNG

[![NPM version][npm-image]][npm-url] [![Downloads][downloads-image]][npm-url]

Thanks to `lagden` and `ozio`

Compress PNG/JPG with TinyPNG API in terminal.
Support multi API keys, if one reaches the limit, automaticly switch to another!

## Installation

    $ npm install -g multi-tinypng


## Usage

```
Usage: tinypng [options] [image.png|*.png]

  -k, --api-key       Set default TinyPNG API key.
  -r, --allow-rewrite Rewrite the original files with compressed data.
  -n, --allow-nonpng  Allow you to compress files without .png extention.
  -p, --postfix       Postfix for compressed files when rewriting disabled.
  -h, --help          This message.
  -v, --version       Show version.
```

[downloads-image]: http://img.shields.io/npm/dm/multi-tinypng.svg
[npm-url]: https://npmjs.org/package/multi-tinypng
[npm-image]: http://img.shields.io/npm/v/multi-tinypng.svg
