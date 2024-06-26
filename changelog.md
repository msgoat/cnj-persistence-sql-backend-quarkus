# Changelog
All notable changes to `cnj-persistence-sql-backend-quarkus` will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [3.0.1] - 2024-04-05
### Fixed
- added missing docker platforms to trigger multi-architecture builds

## [3.0.0] - 2024-03-05
### Changed
- upgraded Quarkus to version 3.8.1
- upgraded some dependencies
- upgraded Java to version 21
- upgraded Maven plugins and dependencies
- build now packages and pushes Helm charts
- deploy now uses packaged Helm charts
- consolidated POM with other showcases
- consolidated system tests with other showcases
- build tags git branch after successful completion
- commit-stage builds produce Docker images for linux/amd64 and linux/arm64/v8 platforms now
- Docker images use Generational Z garbage collector by default
- simplified POM
### Fixed
- improved test coverage measurement with Jacoco to include all coverage data in reports

## [2.1.0] - 2023-08-25
### Added
- added explicit dependency to CloudTrain Maven repository to POM to simplify local builds
- allowed anonymous read access to CloudTrain Maven repository to simplify local builds
- added global docker-compose.yml file to simplify local execution
### Changed
- improved documentation in README.md

## [2.0.0] - 2023-06-07
### Changed
- moved to new AWS CodeBuild build pipeline
- moved to new CloudTrain EKS cluster
- upgraded everything

## [1.2.0] - 2022-09-13
### Added
### Changed
- re-released after repo split
