# Submodule Dependencies Test

This repository contains Git submodules to test dependency detection.

## Submodules

This repository includes:
1. **Local submodule** - References another repository in the same organization (test-dependency-target)
2. **External submodule** - References a public repository (actions/checkout)

## Purpose

Used to test:
- Submodule detection during discovery
- Classification of local vs external dependencies
- Parsing of .gitmodules file
