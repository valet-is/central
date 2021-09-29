# Valet

## Introduction

`Valet` is a command-line toolkit that attached to a set of tools and libraries which helps to develop web applications faster and efficient way.

Thera are multiple components attached `Valet` as listed below:

- CLI
- Server (RESTful API Server)
- react-jetpack

## Getting Started

To get started, you first need to install `valet-cli` on your workstation.

> Prerequisite here is, Node.js installed already.

```bash
npm i @valet-is/cli -g
// or npm i valet-cli -g
```

That's it, you are ready to start.

### Initializing a new application

#### `valet-init`

The `valet init` command will create scaffold RESTful API written in `Node.js`. Default installtion will include minimal source files with `JsonDB` database connector.

```bash
valet init <app> [--console|-c] [--db|-d <jsondb|mongodb>] [--lang|-l <nodejs|golang>]

// eg. valet init my-restful-api -d mongodb -l nodejs
```

##### `--console`

* Type: Boolean
* Default: false

Indicate that whether you need to include console frontend with scaffolded source code.

##### `--db`

* Type: String
* Default: jsondb
* Options: jsondb, mongodb

##### `--lang`

* Type: String
* Default: nodejs
* Options: jsondb, golang
