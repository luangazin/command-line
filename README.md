command-line
============



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/command-line.svg)](https://npmjs.org/package/command-line)
[![Downloads/week](https://img.shields.io/npm/dw/command-line.svg)](https://npmjs.org/package/command-line)
[![License](https://img.shields.io/npm/l/command-line.svg)](https://github.com/luangazin/command-line/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g command-line
$ command-line COMMAND
running command...
$ command-line (-v|--version|version)
command-line/0.1.0 linux-x64 node-v14.18.1
$ command-line --help [COMMAND]
USAGE
  $ command-line COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`command-line hello [FILE]`](#command-line-hello-file)
* [`command-line help [COMMAND]`](#command-line-help-command)

## `command-line hello [FILE]`

describe the command here

```
USAGE
  $ command-line hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ command-line hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/luangazin/command-line/blob/v0.1.0/src/commands/hello.ts)_

## `command-line help [COMMAND]`

display help for command-line

```
USAGE
  $ command-line help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_
<!-- commandsstop -->
