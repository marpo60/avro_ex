# Changelog

## Unreleased

### Fixed
* Fix exception when encoding bad Record data
* Address dialyzer issues
* Add type for AvroEx.Schema.Record.Field to fix compilation error
* Fix long encoding
* Fix variable integer and long decoding

### Added
* Support encoding DateTime and Time to logical types in Union

### Changed
* Records can accept atoms for encoding keys
* String values can accept atoms for encoding
* Enums can accept atoms for encoding
* Simplify integer and long encoding

