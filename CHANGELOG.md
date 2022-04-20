# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

### Fixed

### Added

- Code of conduct
- Add a "Conductor" class for calculating conductivity as a function of temperature.
- Add a "Transformer" class for multi-layer spiral based transformer designs
- Add `frequency_to_skin_depth` and `skin_depth_to_frequency` utility functions

## [v0.1.2]

### Fixed

- Fix error in spiral DC resistance calculation that was omitting the last turn ([issue-10](https://github.com/dzimmanck/python-planar-magnetics/issues/10))
- Fix bug in the code which tries to equalize the area of outer post legs with the centerpost

### Added

## [v0.1.1]

- Fix classifiers for PyPi release

## [v0.1.0]

- Initial release
