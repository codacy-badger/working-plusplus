# Changelog
All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.0.3] - 2018-08-11

### Added
- A framework for providing 'sets' of random messages, each with a configurable probability of being chosen
- A small probability of a 'shifty' response (requires the `:shifty:` emoticon on your Slack team)
- Contributors: many more tests than are probably needed for an app of this size
- Contributors: additional documentation for contributing to this app

### Changed
- Message types now allow for richer formatting, with different components able to be easily moved around
- Contributors: some linting rules have been changed to make them easier to deal with
- Contributors: new `devDependencies` in this release (run `yarn` or `npm install` to update)

## [0.0.2] - 2018-08-09

### Added
- Contributors: testing and linting tools, along with documentation

### Changed
- Contributors: quite a bit of reorganising to make it easier both to grow and to test the app

### Fixed
- Scores of -1 are now referred to as -1 point, rather than -1 points

## [0.0.1] - 2018-08-06

**Initial release.**

Includes:

- Basic karma adding and karma subtracting functionality
- Prevention of self karma giving
- A small selection of random response messages
- Workaround for Heroku free dyno sleeping causing Slack to timeout
- Workaround for iOS automatically replacing -- with an emdash
- Some documentation on installing to Slack and deploying on Heroku

[Unreleased]: https://github.com/tdmalone/working-plusplus/compare/v0.0.3...HEAD
[0.0.3]: https://github.com/tdmalone/working-plusplus/compare/v0.0.2...v0.0.3
[0.0.2]: https://github.com/tdmalone/working-plusplus/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/tdmalone/working-plusplus/compare/456584780...v0.0.1
