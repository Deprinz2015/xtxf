# Changelog

All notable changes to this project will be documented in this file.

## [0.5.1] - 2024-08-30

### Bug Fixes

- Catch `usage` flags
- Print `usage` on errors
- Update description
- Update help prefix

### Operations

- Set zig version in `lint`

### Refactor

- Move `cli` structs
- Drop `child_type_parse_fns`
- Drop parser errors
- Add `opts`
- Use `checkFlag()`

## [0.5.0] - 2024-08-28

### Bug Fixes

- Update argument descriptions
- Rename `pulse` flag
- Change help message types
- Generate meta on native targets
- Check repository state
- Set `help_category_order`

### Documentation

- Reformat usage
- Update example command

### Features

- [**breaking**] Use `cova` for argument parsing
- Add custom usage function
- Reintroduce `version`

### Operations

- Add `build-cross` job
- Add cross build mode

### Refactor

- Drop `Mode`/`Color` switch
- Move `Ghext` to the build system
- Move `time` option

### Build

- Bump cova to `2055b94`
- Fix meta docs

## [0.4.1] - 2024-08-18

### Bug Fixes

- Reformat help message

### Operations

- Set release job name
- Use `gzip`
- Move `Upload` step
- Add missing step names
- Fix `subject-path`

### Refactor

- Add `assets`

### Styling

- Fix yaml formatting

## [0.4.0] - 2024-08-16

### Bug Fixes

- Check gap array status

### Documentation

- Update usage
- Add `Compilation`

### Features

- Add `version`
- Add `Color.magenta`

### Operations

- Configure dependabot
- Set dependabot pr reviewers
- Change dependabot schedule
- Add binary attestation
- Fix `id-token`
- Rename release jobs

### Refactor

- Drop undefined gap arrays
- Rename gap arrays
- Add `Core.start()`
- Add `Handler.init()`

### Testing

- Add `version`
- Add `help`

### Build

- Add ghext
- Bump termbox to `d4128b4`

## [0.3.1] - 2024-07-19

### Bug Fixes

- Add `Core.shutdown()`
- Set `log` scope
- Catch negative dimensions

### Documentation

- Update options
- Comment `pulse`

### Operations

- Drop `xvfb`
- Update build commands

### Refactor

- Add `Core.init()`
- Set default struct values
- Drop `@This()`

### Styling

- Fix `updateTermSize()`

### Testing

- Add `runner()`
- Add color tests

## [0.3.0] - 2024-07-01

### Bug Fixes

- Fix segfault on resize
- Move rendering state
- Drop mutex locks from section functions
- Lock `handler`

### Features

- Add `grid` mode
- Add `blocks` mode

### Miscellaneous tasks

- Add funding

### Operations

- Update `ci` workflow
- Update coverage job
- Add build mode
- Update reusable inputs
- Update build command
- Add labeler
- Add pr template
- Use `release` flag

### Performance

- Point `checkSec()` array
- Optimize stdout print

### Refactor

- Swap `animation()` parameters
- Edit `handler.style` conditions
- Drop mutex locks
- Add `Core.updateStyle()`

### Testing

- Add `decimal`
- Add `grid`

### Build

- Bump termbox to `ff767c1`

## [0.2.1] - 2024-06-22

### Bug Fixes

- Move terminal size check
- Use `process.Child`
- Add `core.allocator`
- Improve terminal size check

### Documentation

- Add coverage badge
- Update usage

### Miscellaneous tasks

- Ignore .zig-cache

### Operations

- Enable tests
- Generate test coverage
- Set zig version on coverage
- Add build summary
- Bump zig to 0.13.0
- Fix kcov integration
- Add codecov settings

### Refactor

- Drop `debug.print()`

### Testing

- Move `main`
- Fix stderr length
- Link libc
- Add `columns`
- Add `crypto`

### Build

- Set unit tests name
- Set test attributes
- Fix root source file

## [0.2.0] - 2024-06-18

### Bug Fixes

- Reformat help message
- Normalize frames
- Fix `core` memory leak
- Move `tb_init()`
- Check terminal size
- Update allowed terminal size
- Sections use `BoundedArrayAligned`

### Documentation

- Add example command

### Features

- Add `color` option
- Add `crypto` mode
- Add `time` option
- Add `Color.green`
- Use bold characters
- Add `columns` mode
- Add `pulse` option
- Add `Color.blue`
- Add `Color.yellow`
- Handle terminal resize

### Operations

- Fix release condition
- Set `cd` zig version

### Refactor

- `stateChange()` -> `setActive()`
- Add `FRAME`
- Drop redundant `core` variables

### Testing

- Add basic test
- Add string test
- Add array test
- Add nth value test
- Expand string test
- Add handler test
- Update handler test
- Add sections test
- Update array tests

## [0.1.0] - 2024-05-23

### Documentation

- Add README.md
- Add status badge
- Add help message

### Features

- Add `printCell()`
- Implement `rand`
- Implement key event
- Add `Core`
- Exit on all events
- Add `decimal` mode
- Improve help message

### Miscellaneous tasks

- Update gitignore
- Add LICENSE
- Add CHANGELOG

### Operations

- Add `ci` workflow
- Set zig version
- Add `cd` workflow
- Update build command
- Update `cd` workflow

### Performance

- Move rendering call

### Build

- Add `termbox2`
- Set `.paths`
- Drop termbox bindings
- Link `libc`


