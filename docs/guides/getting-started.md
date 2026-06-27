---
title: Getting started
sidebar_position: 1
description: Install Doctest and run it for the first time.
---

# Getting started

Install the latest release:

```bash
go install github.com/greenmaskio/doctest@latest
```

Run it against a sample config:

```bash
doctest run --config ./doctest.yaml
```

New in `0.2`: pass `--watch` to re-run on file changes:

```bash
doctest run --config ./doctest.yaml --watch
```

See [Configuration](./configuration.md) for the available options and the
[CLI reference](../reference/cli.md) for every flag.
