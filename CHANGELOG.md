# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- Command `zenio help`
- `zenio help` command is executed by default when a command is not specified

### Fixed
- Create branch procedure will checkout on a branch if it already exists in the local repository

### Chore
- Command `zenio commit` performs `git add`
- Request of VCS authentication token happens on `zenio connect`
- On merge request creation, target branch will be master by default, if the user not specified it

## [0.3.0] - 2019-03-22
### Added
- Command `zenio commit`
- Command `zenio unstart`
- Command `zenio red`
- Command `zenio green`
- GitHub integration
- GitLab integration
- Local storage

### Fixed
- Command `zenio init`
- Command `zenio start`
- Directory for user's properties

## [0.2.0] - 2019-03-15
### Added
- Command `zenio version`

## [0.1.0] - 2019-03-15
### Added
- Command `zenio init`
- Command `zenio connect`
- Command `zenio list`
- Command `zenio start`