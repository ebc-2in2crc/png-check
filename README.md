png-check
=========

png-check は, PNG ファイルのカラータイプと透過設定をチェックするプログラムです.

## Description

png-check は, PNG ファイルのカラータイプ (PNG 8 / 24 / 32) と透過設定 (アルファチャネル / 透過色) をチェックするプログラムです.
グレースケールには対応していません。

## Requirement

- [ImageMagick](https://www.imagemagick.org/script/index.php)

## Usage

```sh
$ png-check png8-non-transparent.png
PNG-8

$ png-check png8-indexed-color.png
PNG-8 (indexed color)

$ png-check png8-alpha.png
PNG-8 (alpha channel)

$ png-check png24.png
PNG-24

$ png-check png32-non-transparent.png
PNG-32

$ png-check png32-alpha.png
PNG-32 (alpha channel)
```

## Installation

Download from the following url.

- [https://github.com/ebc-2in2crc/png-check/releases](https://github.com/ebc-2in2crc/png-check/releases)

Or, you can use Homebrew (Only macOS).

```sh
$ brew tap ebc-2in2crc/png-check
$ brew install png-check
```

## Contribution

1. Fork this repository
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

## Licence

[MIT](https://github.com/ebc-2in2crc/png-check/blob/master/LICENCE)

## Author

[ebc-2in2crc](https://github.com/ebc-2in2crc)
