# @rage-js/cli

## 1.3.1

### Patch Changes

- 324e67d: 
  ## Bug Fix:
  - Removed `process.cwd()` from `cli` module, as per [Issue #44](https://github.com/rage-js/core/issues/44) on `core` package repository.

## 1.3.0

### Minor Changes

- 79ae796: 
  - Feature: No Interval method is now available to select.
  - Feature: `loopStartDelay` attribute is now prompted with `5000` milliseconds default value.

## 1.2.9

### Patch Changes

  - Bug fix: Replace `@rage-js/cli` package with `@rage-js/tools` on the `package.json` file content when creating one using the CLI.
  - Bug fix: Add `const` to `app` on the ESM version of the main file content.
  - Bug fix: Removed `"exit" || "SIGTERM" || "SIGINT"` conditional exit signals because of it causing an error when integrating RAGE with `express`.

## 1.2.8

### Patch Changes

  - Feature: Added `@rage-js/cli` package to `package.json`'s dependencies created by the CLI.
  - Comment: Added a comment on line `425` to explain the reason for importing file contents for the main files statically instead of dynamic.

## 1.2.7

### Patch Changes

 - Added new logo and shown it on README

## 1.2.6

### Patch Changes

 - File content exit function fixed

## 1.2.5

### Patch Changes

 - Updated file content for main javascript files

## 1.2.4

### Patch Changes

 - Final patch

## 1.2.3

### Patch Changes

 - File content bug fixed again

## 1.2.2

### Patch Changes

 - Fixed file content again

## 1.2.1

### Patch Changes

 - Bug on creating file content

## 1.2.0

### Minor Changes

 - Finally added main js file content

## 1.1.0

### Minor Changes

 - Default value added to outDir
