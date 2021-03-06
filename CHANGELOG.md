# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [1.6.4] - 2018-07-25
### Fixed
- Only set state if mounted

## [1.6.3] - 2018-05-31
### Fixed
- README.md example

## [1.6.2] - 2018-05-28
### Added
- doc disableNative on README.md

## [1.6.1] - 2018-05-04
### Changed
- update: devDeps

## [1.6.0] - 2018-04-04
### Added
- Implements prop for disabling native browser confirmation

### Changed
- Update test script.

## [1.5.8] - 2018-03-18
### Fixed
- Only call when once from the block function.

## [1.5.7] - 2018-02-20
### Fixed
- Make prevUserAction an instance instead of module property

## [1.5.6] - 2018-02-20
### Fixed
- use entire location when navigation is confirmed

## [1.5.5] - 2018-01-23
### Changed
- Improve README

## [1.5.4] - 2018-01-22
### Added
- include package-lock.json in the repo

### Fixed
- make afterConfirm, afterCancel callable

## [1.5.3] - 2017-12-21
### Fixed
- Make react-router-dom an external dependency

## [1.5.2] - 2017-10-27
### Changed
- Update README

## [1.5.1] - 2017-10-25
### Fixed
- When action is `"POP"`, push (
We cannot know the correct history entry to pop to without using memory history - (https://github.com/ReactTraining/history#properties).)

## [1.5.0] - 2017-10-25
### Added
- props.when can be a function taking (crntLocation, nextLocation)

## [1.4.0] - 2017-10-24
### Added
- props.beforeCancel()
- props.beforeConfirm()
- props.afterCancel()
- props.afterConfirm()

## [1.3.0] - 2017-10-23
### Added
- tool: eslint

## [1.2.3] - 2017-10-23
### Fixed
- Handle history.pop()/history.goBack() correctly

## [1.2.2] - 2017-10-23
### Fixed
- build did not reflect src code

## [1.2.1] - 2017-10-23
### Fixed
- Access fresh props in history.block()'s callback

## [1.2.0] - 2017-10-23
### Added
- this.props.renderIfNotActive

## [1.1.2] - 2017-10-23
### Fixed
- build did not reflect src code

## [1.1.1] - 2017-10-23
### Fixed
- package.json

## [1.1.0] - 2017-10-22
### Changed
- Confirm navigation away from site

## [1.0.1] - 2017-10-22
### Added
- doc: Important caveat

## [1.0.0] - 2017-10-22
###
- this project's useable existence

## Older stuff
- why?
