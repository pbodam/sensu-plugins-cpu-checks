# Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## [Unreleased]
### Added
- ruby 2.4 testing (@majormoses)

### Fixed
- PR template spell "Compatibility" correctly (@majormoses)
- made bin executable (@majormoses)

## [1.1.2] - 2017-06-20
### Fixed
- `metrics-cpu.rb`/`metrics-cpu-pcnt-usage.rb`: Set the correct type for --proc-path (@bimlendu)

## [1.1.1] - 2017-05-02
### Changed
- no real change just bumping due to deployment issue.

## [1.1.0] - 2017-05-02
### Added
- check-cpu.rb: added option to check less than (@santhosh-tekuri)
- check-cpu.rb: added option to use a cache file rather than sleeping to look at previous times (@axos88)

### Fixed
- Set the correct type for --proc-path (@envintus)
- metrics-cpu.rb was missing a column (@michau)

## [1.0.0] - 2016-06-15
### Changed
- Modified check-cpu.rb to change state if >= threshold
- Updated Rubocop to 0.40, applied auto-correct
- Loosened sensu-plugin dependency to ~> 1.2
- Specify the /proc location for use within a container

### Added
- Added metrics-numastat.rb
- check-cpu.rb: Added --idle-metrics flag for indicating counters which should be considered idle

### Removed
- Remove Ruby 1.9.3 support; add Ruby 2.3.0 support in test matrix

## [0.0.4] - 2015-09-29
### Changed
- Fix getopts syntax in check-cpu.sh
- Improvements to system/metrics-user-pct-usage.rb (option to use uid instead of username)

## [0.0.3] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## [0.0.2] - 2015-06-02
### Fixed
- added binstubs

### Changed
- removed cruft from /lib

## 0.0.1 - 2015-05-21
### Added
- initial release


[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-cpu-checks/compare/1.1.2...HEAD
[1.1.2]: https://github.com/sensu-plugins/sensu-plugins-cpu-checks/compare/1.1.1...1.1.2
[1.1.1]: https://github.com/sensu-plugins/sensu-plugins-cpu-checks/compare/1.1.0...1.1.1
[1.1.0]: https://github.com/sensu-plugins/sensu-plugins-cpu-checks/compare/1.0.0...1.1.0
[1.0.0]: https://github.com/sensu-plugins/sensu-plugins-cpu-checks/compare/0.0.4...1.0.0
[0.0.4]: https://github.com/sensu-plugins/sensu-plugins-cpu-checks/compare/0.0.3...0.0.4
[0.0.3]: https://github.com/sensu-plugins/sensu-plugins-cpu-checks/compare/0.0.2...0.0.3
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-cpu-checks/compare/0.0.1...0.0.2
