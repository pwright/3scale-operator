# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

## [0.5.0] - 2020-04-02

### Added
- APIManager CRD 3scale 2.8
- Upgrade between 2.7 and 2.8 (no specific PR, implementation distributed in feature PR's)
- Metrics endpoint include 3scale operator and product version [#290](https://github.com/3scale/3scale-operator/pull/290)
- Move system-smtp to secret [#280](https://github.com/3scale/3scale-operator/pull/280)
- Support s3 apicompatible service [#302](https://github.com/3scale/3scale-operator/pull/302)
- Add support for PodDisruptionBudget [#308](https://github.com/3scale/3scale-operator/pull/308)
- Operator-sdk v0.15.2 Go version v1.13 [#331](https://github.com/3scale/3scale-operator/pull/331)

## [0.4.0] - 2019-11-28

### Added
- APIManager CRD 3scale 2.7
- Make replicas configurable in scalable DeploymentConfigs [#220](https://github.com/3scale/3scale-operator/pull/220)
- Upgrade between 2.6 and 2.7 [#203](https://github.com/3scale/3scale-operator/pull/203)

## [0.3.0] - 2019-11-06

### Added
- APIManager CRD 3scale 2.6
- Migrate DBs to imagestreams [#122](https://github.com/3scale/3scale-operator/pull/122)
- Operator-sdk v0.8.0 [#126](https://github.com/3scale/3scale-operator/pull/126)
- Authenticated registry.redhat.io [#124](https://github.com/3scale/3scale-operator/pull/124)
- PostgreSQL support [#129](https://github.com/3scale/3scale-operator/pull/129)
- Wildcard router removed [#135](https://github.com/3scale/3scale-operator/pull/135)
- Redis sentinels [#137](https://github.com/3scale/3scale-operator/pull/137)
- Zync-Que [#145](https://github.com/3scale/3scale-operator/pull/145)
- OLM catalog [#71](https://github.com/3scale/3scale-operator/pull/71)

## [0.2.0] - 2019-04-02

### Added
- APIManager CRD 3scale 2.5
- Tenants CRD
- Capabilities CRD (api, limit, plan, binding, metric, mappingrule)

### Added

[Unreleased]: https://github.com/3scale/3scale-operator/compare/v0.5.0...HEAD
[0.5.0]: https://github.com/3scale/3scale-operator/releases/tag/v0.5.0
[0.4.0]: https://github.com/3scale/3scale-operator/releases/tag/v0.4.0
[0.3.0]: https://github.com/3scale/3scale-operator/releases/tag/v0.3.0
[0.2.0]: https://github.com/3scale/3scale-operator/releases/tag/v0.2.0
