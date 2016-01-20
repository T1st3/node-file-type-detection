
> a list of file-type detection and extension-list modules for Node.js

## About

Modules named `is-*` are conventional detectors for the `file-type.*`. All these modules detect whether the file is of the expected type using Buffer/Uint8Array.

Modules named `*-extensions` are conventional lists of extensions for a category of file types, aggregated in a JSON file.

## Table of Contents

- [Generic](#generic)
- [Archive](#archive)
- [Image](#image)
- [Audio](#audio)
- [Videos](#video)


## Generic

One detector to rule them all: this module detects many formats, using Buffer/Uint8Array. It is a generic module; if you want to detect a specific file type, please check below for more specific detectors.

- [file-type](https://github.com/sindresorhus/file-type)

## Archive

### Extension list

- [archive-extensions](https://github.com/sindresorhus/archive-extensions)

### Detectors

- [is-zip](https://github.com/kevva/is-zip)
- [is-tar](https://github.com/kevva/is-tar)
- [is-gzip](https://github.com/kevva/is-gzip)
- [is-bzip2](https://github.com/kevva/is-bzip2)
- [is-xz](https://github.com/kevva/is-xz)
- [is-7z](https://github.com/T1st3/is-7z)
- [is-rar](https://github.com/kevva/is-rar)

## Image

### Extension list

- [image-extensions](https://github.com/arthurvr/image-extensions)

### Detectors

- [is-gif](https://github.com/sindresorhus/is-gif)
- [is-jpg](https://github.com/sindresorhus/is-jpg)
- [is-png](https://github.com/sindresorhus/is-png)
- [is-webp](https://github.com/sindresorhus/is-webp)
- [is-tif](https://github.com/sindresorhus/is-tif)

## Audio


## Video


## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [T1st3](http://www.tiste.org) has waived all copyright and related or neighboring rights to this work.
