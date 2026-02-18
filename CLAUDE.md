# CLAUDE.md — example-interactive-installation

**ORGAN II** (Art) · `organvm-ii-poiesis/example-interactive-installation`
**Status:** ACTIVE · **Branch:** `main`

## What This Repo Is

Reference implementation for sensor-driven interactive art installations with depth cameras, LIDAR, and spatial audio

## Stack

**Languages:** Python
**Build:** Python (pip/setuptools)
**Testing:** pytest (likely)

## Directory Structure

```
📁 .github/
📁 docs/
    adr
📁 examples/
📁 presets/
📁 renderers/
📁 src/
    __init__.py
    config.py
    engine.py
    mapping.py
    output.py
    sensor_sim.py
📁 tests/
    __init__.py
    test_config.py
    test_engine.py
    test_mapping.py
    test_renderers.py
    test_sensor_sim.py
  .gitignore
  CHANGELOG.md
  LICENSE
  README.md
  pyproject.toml
  seed.yaml
```

## Key Files

- `README.md` — Project documentation
- `pyproject.toml` — Python project config
- `seed.yaml` — ORGANVM orchestration metadata
- `src/` — Main source code
- `tests/` — Test suite

## Development

```bash
pip install -e .    # Install in development mode
pytest              # Run tests
```

## ORGANVM Context

This repository is part of the **ORGANVM** eight-organ creative-institutional system.
It belongs to **ORGAN II (Art)** under the `organvm-ii-poiesis` GitHub organization.

**Dependencies:**
- organvm-ii-poiesis/metasystem-master

**Registry:** [`registry-v2.json`](https://github.com/meta-organvm/organvm-corpvs-testamentvm/blob/main/registry-v2.json)
**Corpus:** [`organvm-corpvs-testamentvm`](https://github.com/meta-organvm/organvm-corpvs-testamentvm)
