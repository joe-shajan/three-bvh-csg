# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [0.0.8] - 2023-07-08
### Fixed
- Peer dependencies to allow three versions >= r144

## [0.0.7] - 2023-06-07
### Fixed
- Typo when changing SphereBufferGeometry.

## [0.0.6] - 2023-06-06
### Changed
- Updated to support three.js versions >= 154

## [0.0.5] - 2023-03-27
### Fixed
- Improve types.

## [0.0.4] - 2023-01-20
### Fixed
- Case where very thin triangles would not be clipped.
- Simplified clipping logic and removed case where clipping could cause a log from unexpected scenario.

## [0.0.3] - 2023-01-17
### Added
- Typescript definitions for the public API.
- Support for geometries with negated scales.
- `computeMeshVolume` function.

### Fixed
- Return value for GridMaterial.getCustomCacheKey().
- Made coplanar face intersections more robust.
- Case where coplanar faces were not handled properly with the `DIFFERENCE` operation.
- Handle `COPLANAR` cases more robustly.
- Improved half edge precision.

## [0.0.2] - 2022-09-15
### Fixed
- Incorrect package.json "main" reference.

## [0.0.1] - 2022-07-19

Initial experimental version.
