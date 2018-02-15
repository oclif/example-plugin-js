@oclif/example-plugin-js
========================

example dxcli plugin in javascript

[![Version](https://img.shields.io/npm/v/@oclif/example-plugin-js.svg)](https://npmjs.org/package/@oclif/example-plugin-js)
[![CircleCI](https://circleci.com/gh/oclif/example-plugin-js/tree/master.svg?style=svg)](https://circleci.com/gh/oclif/example-plugin-js/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/oclif/example-plugin-js?branch=master&svg=true)](https://ci.appveyor.com/project/heroku/example-plugin-js/branch/master)
[![Codecov](https://codecov.io/gh/oclif/example-plugin-js/branch/master/graph/badge.svg)](https://codecov.io/gh/oclif/example-plugin-js)
[![Greenkeeper](https://badges.greenkeeper.io/oclif/example-plugin-js.svg)](https://greenkeeper.io/)
[![Known Vulnerabilities](https://snyk.io/test/github/oclif/example-plugin-js/badge.svg)](https://snyk.io/test/github/oclif/example-plugin-js)
[![Downloads/week](https://img.shields.io/npm/dw/@oclif/example-plugin-js.svg)](https://npmjs.org/package/@oclif/example-plugin-js)
[![License](https://img.shields.io/npm/l/@oclif/example-plugin-js.svg)](https://github.com/oclif/example-plugin-js/blob/master/package.json)

<!-- toc -->
* [Install](#install)
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
<!-- install -->
# Install

with yarn:
```
$ yarn global add @oclif/example-plugin-js
```

or with npm:
```
$ npm install -g @oclif/example-plugin-js
```
<!-- installstop -->
<!-- usage -->
# Usage

```sh-session
$ oclif-example COMMAND
running command...
$ oclif-example (-v|--version|version)
@oclif/example-plugin-js/1.2.14 (linux-x64) node-v9.5.0
$ oclif-example --help [COMMAND]
USAGE
  $ oclif-example COMMAND
...
```
<!-- usagestop -->
<!-- commands -->
# Commands

* [oclif-example hello](#hello)
## hello

Describe the command here

```
USAGE
  $ oclif-example hello

OPTIONS
  -n, --name=name  name to print

DESCRIPTION
  Describe the command here
  ...
  Extra documentation goes here
```

_See code: [src/commands/hello.js](https://github.com/oclif/example-plugin-js/blob/v1.3.0/src/commands/hello.js)_
<!-- commandsstop -->
