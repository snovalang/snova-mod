# Snova Mod (`Snova.Std.Mod`)

Module and dependency management in pure Snovalang adhering to Go modules semantics.

## Features
- `Version` SemVer 2.0.0 parser and comparator (`isGreaterThan`)
- `ModFile` generator and parser for `snova.mod`
- `GitProviderResolver` for resolving canonical git URLs (`github.com`, `gitlab.com`, etc.)
