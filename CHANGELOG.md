# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project aims to adhere to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased
### Added

### Changed

### Fixed

### Removed

## 1.4.1 (Monday, 24 August, 2020)
### Fixed
- Set proper defaults for Postman overrides, handle empt array examples in OAS (https://github.com/knuckleswtf/scribe/pull/77)

## 1.4.0 (Sunday, 23 August, 2020)
### Added
- Support for resourceKey in Transformers(https://github.com/knuckleswtf/scribe/pull/73)
- OpenAPI (Swagger) spec generation (https://github.com/knuckleswtf/scribe/pull/75)
- Ability to override specific fields in generated Postman collection and OpenAPI spec (https://github.com/knuckleswtf/scribe/pull/76)

## 1.3.0 (Friday, 17 July, 2020)
### Fixed
- Provided option to bypass database drivers that don't support transactions (https://github.com/knuckleswtf/scribe/pull/55, https://github.com/knuckleswtf/scribe/pull/57)

## 1.2.0 (Sunday, 5 July, 2020)
### Added
- Include raw request URL in Postman collection (https://github.com/knuckleswtf/scribe/pull/43)

## 1.1.1 (Friday, 3 July, 2020)
### Fixed
- Support HEAD-only endpoints (https://github.com/knuckleswtf/scribe/pull/54)

## 1.1.0 (Monday, 1 June, 2020)
### Modified
- Added ability to set postman base_url independently (https://github.com/knuckleswtf/scribe/pull/31)

## 1.0.3 (Monday, 25 May, 2020)
### Modified
- Updated dependencies (https://github.com/knuckleswtf/scribe/pull/26)

## 1.0.2 (Sunday, 24 May, 2020)
### Fixed
- Set badge colour for OPTIONS method too. (https://github.com/knuckleswtf/scribe/commit/ccce82cf75502493d776a4ec2378de9cda1659f3)

## 1.0.1 (Saturday, 23 May, 2020)
### Fixed
- Pinned erusev/parsedown dependency (from mnapoli/front-yaml) to ^1.7.4 to fix incompatibilities. (https://github.com/knuckleswtf/scribe/commit/fd623238852dca0e77aa88e86220830d71a460d4)

## 1.0.0 (Saturday, 23 May, 2020)
See [what's new](https://scribe.readthedocs.io/en/latest/whats-new.html) and the [migration guide](https://scribe.readthedocs.io/en/latest/migrating.html).
