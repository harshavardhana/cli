---
title: Exoscale CLI
description: |
    Manage easily your Exoscale infrastructure from the command-line with `exo`.

---

[![Build Status](https://travis-ci.com/exoscale/cli.svg?branch=master)](https://travis-ci.com/exoscale/cli) [![Go Report Card](https://goreportcard.com/badge/github.com/exoscale/cli)](https://goreportcard.com/report/github.com/exoscale/cli) [![Docker image](https://images.microbadger.com/badges/image/exoscale/cli.svg)](https://microbadger.com/images/exoscale/cli "Get your own image badge on microbadger.com")

## Installation

The easiest way is to follow [the tutorial on the Exoscale command-line interface][community].

### Manual compilation

This project is open source and may be modified, studied, and built at will. We use and recommend Go 1.11+

```shell
# clone it
$ git clone https://github.com/exoscale/cli
$ cd cli

# run it
$ go run main.go

# build it
$ go build -mod vendor -o exo
```

## Configuration

The CLI will guide you in the initial configuration.

You can find your credentials in our [Exoscale Console](https://portal.exoscale.com/account/profile/api) (having or creating an account is required).

```shell
$ exo config
```

The configuration file and all assets created by any `exo` command will be saved in the `.exoscale` folder inside your home directory.

## Usage

```shell
$ exo --help
```

[community]: https://community.exoscale.com/documentation/tools/exoscale-command-line-interface/

## Powered by

- [cobra](https://github.com/spf13/cobra), by Steve Francia :us:
- [mpb](https://github.com/vbauerster/mpb), by Vladimir Bauer :ru:
- [tablewriter](https://github.com/olekukonko/tablewriter), by Oleku Konku
- [chroma](https://github.com/alecthomas/chroma), by Alec Thomas :australia:
