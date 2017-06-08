# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [1.1.0] - 2017-06-09
### Changed
- Hostname pattern to establish network connections with containers changed from `(container_name.)image_name.docker` to `(instance_id.)module_name.docker`
### Added
- Possibility to configure extensions in pom.xml files
### Fixed
- Prevent NPE when programmatically adding modules that have no labels or properties
- e2e tests randomly freezing
## [1.0.0] - 2015-10-06

Intitial release. 