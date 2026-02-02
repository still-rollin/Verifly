# Verifly 🚀

**Verifly** is a GitHub Action for fast Lean proof verification.

## Usage

Add this workflow to your Lean project:

```yaml
name: Verifly

on:
  push:
  pull_request:

jobs:
  verify:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: still-rollin/verifly@v1

