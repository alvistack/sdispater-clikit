# Change Log

## [0.3.0] - 2019-06-24

### Added

- Added support for displaying multiple, independent progress bars.

### Fixed

- Fixed similar command names suggestions.
- Fixed the `help` command not displaying the help text of commands.


## [0.2.4] - 2019-05-11

### Fixed

- Fixed `help` command not displaying help for sub commands.
- Fixed possible errors for raised exceptions with a non-int `code` attribute.


## [0.2.3] - 2018-12-10

### Fixed

- Fixed handling of ANSI support detection in output.


## [0.2.2] - 2018-12-08

### Changed

- Write line methods will now always write `\n` instead of `os.linesep`.


## [0.2.1] - 2018-12-07

### Changed

- The `help` command will now insert the script name and command name where needed.

### Fixed

- Fixed handling of paragraph in help.


## [0.2.0] - 2018-12-06

### Added

- Added a basic event system.
- Added a `NullIO` class for no-op IO operations.
- Added a progress bar component.
- Added a `hidden` property on command configurations.

### Fixed

- Fixed help display for multi valued options.
- Fixed the progress indicator component.


[Unreleased]: https://github.com/sdispater/tomlkit/compare/0.3.0...master
[0.3.0]: https://github.com/sdispater/tomlkit/releases/tag/0.3.0
[0.2.4]: https://github.com/sdispater/tomlkit/releases/tag/0.2.4
[0.2.3]: https://github.com/sdispater/tomlkit/releases/tag/0.2.3
[0.2.2]: https://github.com/sdispater/tomlkit/releases/tag/0.2.2
[0.2.1]: https://github.com/sdispater/tomlkit/releases/tag/0.2.1
[0.2.0]: https://github.com/sdispater/tomlkit/releases/tag/0.2.0
[0.1.0]: https://github.com/sdispater/tomlkit/releases/tag/0.1.0
