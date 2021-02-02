ghorg
=====

A command line tool for GitHub organization management.

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/ghorg.svg)](https://npmjs.org/package/ghorg)
[![Downloads/week](https://img.shields.io/npm/dw/ghorg.svg)](https://npmjs.org/package/ghorg)
[![License](https://img.shields.io/npm/l/ghorg.svg)](https://github.com/raptazure/ghorg-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g ghorg
$ ghorg COMMAND
running command...
$ ghorg (-v|--version|version)
ghorg/0.1.0 darwin-x64 node-v14.2.0
$ ghorg --help [COMMAND]
USAGE
  $ ghorg COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`ghorg hello [FILE]`](#ghorg-hello-file)
* [`ghorg help [COMMAND]`](#ghorg-help-command)

## `ghorg hello [FILE]`

describe the command here

```
USAGE
  $ ghorg hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ ghorg hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/raptazure/ghorg-cli/blob/v0.1.0/src/commands/hello.ts)_

## `ghorg help [COMMAND]`

display help for ghorg

```
USAGE
  $ ghorg help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.1/src/commands/help.ts)_
<!-- commandsstop -->
