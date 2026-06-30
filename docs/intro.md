---
title: Introduction
sidebar_position: 1
description: Doctest — a sample product docs repo used to exercise the multi-product embedding and versioned delivery pipeline.
---

# Doctest

Welcome to **Doctest**, a sample documentation product. Its only job is to be _real_:
a standalone repo of pure Markdown content that the Greenmask site pulls in as a git
submodule and serves as its own docs instance at `/docs/doctest`.

This repo carries **no build tooling, no config, no JavaScript** — just `docs/**` and
`_category_.json` files. The site owns Docusaurus; this repo owns content. Tag a release
and the site embeds it; that is the whole contract.

## What's here

- [Getting started](./guides/getting-started.md) — install and run.
- [Configuration](./guides/configuration.md) — the config file reference.
- [CLI reference](./reference/cli.md) — every command and flag _(new in 0.2)_.

## Versioning

Doc versions are `major.minor` release **lines** derived from this repo's git tags. The
newest line is the live docs; older lines stay browsable, regenerated from their tags at
build time. You are reading the `0.2` line — switch lines with the version dropdown.

### Test item
