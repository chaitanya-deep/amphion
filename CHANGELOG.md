## [Unreleased]
### Added

### Removed

### Changed

### Fixed

## [0.1.20] - 2019-11-14
### Added
1. Added support for image streams via web-video-server
2. Pointcloud now uses a decoder in wasm (npm: `pcl-decoder`)
3. Added loop option to displaytrajectory
4. Added support for depthcloud stream

### Fixed
1. Fix editor controls import in examples

## [0.1.14] - 2019-10-22
### Added
- Interactive Markers
- Text view-facing markers

### Changed
- Upgrade Three.js and eslint
- Change from window.onresize to using resize observer for viewers
- Markers now support lifetime

### Fixed
- Husky now works only on staged files (lint-staged)

## [0.1.13] - 2019-09-18
### Added
- Wrench
- Range

### Fixed
- 2D viewer camera rotate

## [0.1.12] - 2019-08-27
### Changed
- Updated Three.js and eslint config
- Updated eslint-utils

### Fixed
- Handle is_diff in robot scene attached collision objects for planning

## [0.1.11] - 2019-08-22
### Added
- Pointcloud color, intensity channels
- Pointcloud performance optimizations
- Support more image encodings
- Planning scene trajectory collision

### Changed
- Axis of scene is now z-axis

### Fixed
- Pointcloud rendering
