# generator-phinm

[![Greenkeeper badge](https://badges.greenkeeper.io/LasaleFamine/generator-phinm.svg)](https://greenkeeper.io/)
[![Build Status](https://travis-ci.org/LasaleFamine/generator-phinm.svg?branch=master)](https://travis-ci.org/LasaleFamine/generator-phinm)
[![codecov](https://codecov.io/gh/LasaleFamine/generator-phinm/branch/master/graph/badge.svg)](https://codecov.io/gh/LasaleFamine/generator-phinm)

> Scaffold out a node module. Inspired and forked from [sindresorhus/generator-nm](https://github.com/sindresorhus/generator-nm)

Optionally with a [CLI](http://en.wikipedia.org/wiki/Command-line_interface).

You need [yo](https://github.com/yeoman/yo) to use the generator.

## Install

```
$ npm install --global yo generator-phinm
```


## Usage

```
$ yo phinm
```

There are multiple command-line options available:

```
$ yo phinm --help

  Usage:
    yo phinm [options]

  Options:
    --help          # Print the generator's options and usage
    --skip-cache    # Do not remember prompt answers                      Default: false
    --skip-install  # Do not automatically install dependencies           Default: false
    --org           # Publish to a GitHub organization account
    --cli           # Add a CLI
    --appveyor      # Add Appveyor config file
    --coverage      # Add code coverage with nyc
    --codecov       # Upload coverage to codecov.io (implies --coverage)
```

The `--org` option takes a string value (i.e. `--org=avajs`). All others are boolean flags and can be negated with the `no` prefix (i.e. `--no-codecov`). You will be prompted for any options not passed on the command-line.


## Tip

Use [chalk](https://github.com/sindresorhus/chalk) if you want colors in your CLI.


## License

MIT © [LasaleFamine](https://godev.space)
