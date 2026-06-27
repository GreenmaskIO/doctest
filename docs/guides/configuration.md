---
title: Configuration
sidebar_position: 2
description: The Doctest YAML configuration file.
---

# Configuration

Doctest reads a single YAML file:

```yaml
# doctest.yaml
name: my-suite
verbose: false
paths:
  - ./docs
```

| Key | Type | Default | Description |
| --- | --- | --- | --- |
| `name` | string | `default` | A label for the run. |
| `verbose` | bool | `false` | Emit per-file diagnostics. |
| `paths` | list | `[]` | Directories to scan. |
