# Obliterate

A CLI to obliterate a folder.  It uses [rimraf](https://npmjs.org/package/rimraf) to recursively delete all subdirectories and files contained.  There is no API because it literally just calls rimraf.

## Installation

```
npm install obliterate -g
```

## Usage

```
Usage: obliterate <path>

  Deletes all files and folders at "path" recursively.

Options:

  -h, --help    Display this usage info
```

## License

MIT