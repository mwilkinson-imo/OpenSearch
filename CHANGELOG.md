# CHANGELOG
Inspired from [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [Unreleased]
### Added
- Github workflow for changelog verification ([#4085](https://github.com/opensearch-project/OpenSearch/pull/4085))
- Added @dreamer-89 as an Opensearch maintainer ([#4342](https://github.com/opensearch-project/OpenSearch/pull/4342))
- Added release notes for 1.3.5 ([#4343](https://github.com/opensearch-project/OpenSearch/pull/4343))
- Added release notes for 2.2.1 ([#4344](https://github.com/opensearch-project/OpenSearch/pull/4344))
- Label configuration for dependabot PRs ([#4348](https://github.com/opensearch-project/OpenSearch/pull/4348))
- Support for HTTP/2 (server-side) ([#3847](https://github.com/opensearch-project/OpenSearch/pull/3847))
### Dependencies
- Bumps `com.diffplug.spotless` from 6.9.1 to 6.10.0

### Changed
- Dependency updates (httpcore, mockito, slf4j, httpasyncclient, commons-codec) ([#4308](https://github.com/opensearch-project/OpenSearch/pull/4308))
- Use RemoteSegmentStoreDirectory instead of RemoteDirectory ([#4240](https://github.com/opensearch-project/OpenSearch/pull/4240))
- Plugin ZIP publication groupId value is configurable ([#4156](https://github.com/opensearch-project/OpenSearch/pull/4156))

### Deprecated

### Removed

### Fixed
- `opensearch-service.bat start` and `opensearch-service.bat manager` failing to run ([#4289](https://github.com/opensearch-project/OpenSearch/pull/4289))
- PR reference to checkout code for changelog verifier ([#4296](https://github.com/opensearch-project/OpenSearch/pull/4296))
- `opensearch.bat` and `opensearch-service.bat install` failing to run, missing logs directory ([#4305](https://github.com/opensearch-project/OpenSearch/pull/4305))
- Restore using the class ClusterInfoRequest and ClusterInfoRequestBuilder from package 'org.opensearch.action.support.master.info' for subclasses ([#4307](https://github.com/opensearch-project/OpenSearch/pull/4307))
- Do not fail replica shard due to primary closure ([#4133](https://github.com/opensearch-project/OpenSearch/pull/4133))
- Add timeout on Mockito.verify to reduce flakyness in testReplicationOnDone test([#4314](https://github.com/opensearch-project/OpenSearch/pull/4314))
- Commit workflow for dependabot changelog helper ([#4331](https://github.com/opensearch-project/OpenSearch/pull/4331))
- Token usage for dependabot changelog helper ([#4351](https://github.com/opensearch-project/OpenSearch/pull/4351))

### Security
- CVE-2022-25857 org.yaml:snakeyaml DOS vulnerability ([#4341](https://github.com/opensearch-project/OpenSearch/pull/4341))

## [2.x]
### Added
- Github workflow for changelog verification ([#4085](https://github.com/opensearch-project/OpenSearch/pull/4085))
- Label configuration for dependabot PRs ([#4348](https://github.com/opensearch-project/OpenSearch/pull/4348))

### Changed

### Deprecated

### Removed

### Fixed
- PR reference to checkout code for changelog verifier ([#4296](https://github.com/opensearch-project/OpenSearch/pull/4296))
- Commit workflow for dependabot changelog helper ([#4331](https://github.com/opensearch-project/OpenSearch/pull/4331))

### Security


[Unreleased]: https://github.com/opensearch-project/OpenSearch/compare/2.2.0...HEAD
[2.x]: https://github.com/opensearch-project/OpenSearch/compare/2.2.0...2.x