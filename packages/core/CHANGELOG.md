# Changelog

## 0.2.2

### Patch Changes

- 910284a: Fix transform hook bug

## 0.2.1

### Patch Changes

- 0eb82f0: Adds the `filePath` option, which supports loading a config file from a user-specified input path
- 806cfa6: Fix Windows compatability issue

## v0.2.0

**Features**

- Introduce the `mustExist` flag, which controls Proload's behavior when a configuration is not found.
- Introduce the `ProloadError` class export, which can be used in `instanceof` checks to determine if an Error is coming from Proload internals or somewhere else.

**Docs**

- Document the `mustExist` flag

## v0.1.4

**Fixes**

- Do not attempt to resolve "extends" for unrecognized formats.

## v0.1.3

**Fixes**

- Improves accuracy of TypeScript declarations for CJS entrypoint.

**Docs**

- Added inline documentation to the TypeScript declarations.

## v0.1.2

**Chores**

- Exclude `test` files from package

## v0.1.1

**Added**

- Custom `accept` handler exposes complete control over resolution logic

**Docs**

- Added examples and more detail to README
- Added docs on `accept` handler

## v0.1.0

Initial release
