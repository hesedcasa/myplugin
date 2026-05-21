myplugin
=================

A new CLI generated with oclif


[![Version](https://img.shields.io/npm/v/@hesed/myplugin.svg)](https://npmjs.org/package/@hesed/myplugin)
[![Downloads/week](https://img.shields.io/npm/dw/@hesed/myplugin.svg)](https://npmjs.org/package/@hesed/myplugin)


<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g myplugin
$ my COMMAND
running command...
$ my (--version)
myplugin/0.0.0 darwin-arm64 node-v22.14.0
$ my --help [COMMAND]
USAGE
  $ my COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`my auth add`](#my-auth-add)
* [`my auth test`](#my-auth-test)
* [`my hello PERSON`](#my-hello-person)
* [`my hello world`](#my-hello-world)

## `my auth add`

Add authentication

```
USAGE
  $ my auth add [--json] [-e <value>] [-p <value>] [-t <value>] [-u <value>]

FLAGS
  -e, --email=<value>    Account email
  -p, --profile=<value>  Profile name
  -t, --token=<value>    API Token
  -u, --url=<value>      API endpoint URL (start with https://)

GLOBAL FLAGS
  --json  Format output as json.

DESCRIPTION
  Add authentication

EXAMPLES
  $ my auth add

  $ my auth add --p work
```

_See code: [@hesed/plugin-lib](https://github.com/hesedcasa/plugin-lib/blob/v0.1.1/src/commands/auth/add.ts)_

## `my auth test`

Test authentication and connection

```
USAGE
  $ my auth test [--json] [-p <value>]

FLAGS
  -p, --profile=<value>  Authentication profile name

GLOBAL FLAGS
  --json  Format output as json.

DESCRIPTION
  Test authentication and connection

EXAMPLES
  $ my auth test

  $ my auth test --p work
```

_See code: [@hesed/plugin-lib](https://github.com/hesedcasa/plugin-lib/blob/v0.1.1/src/commands/auth/test.ts)_

## `my hello PERSON`

Say hello

```
USAGE
  $ my hello PERSON -f <value>

ARGUMENTS
  PERSON  Person to say hello to

FLAGS
  -f, --from=<value>  (required) Who is saying hello

DESCRIPTION
  Say hello

EXAMPLES
  $ my hello friend --from oclif
  hello friend from oclif! (./src/commands/hello/index.ts)
```

_See code: [src/commands/hello/index.ts](https://github.com/hesedcasa/myplugin/blob/v0.0.0/src/commands/hello/index.ts)_

## `my hello world`

Say hello world

```
USAGE
  $ my hello world

DESCRIPTION
  Say hello world

EXAMPLES
  $ my hello world
  hello world! (./src/commands/hello/world.ts)
```

_See code: [src/commands/hello/world.ts](https://github.com/hesedcasa/myplugin/blob/v0.0.0/src/commands/hello/world.ts)_
<!-- commandsstop -->
