# Changelog
All notable changes to this chart will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased] 
## [1.1.3] - 2020-03-26
### Updated
- Added admin flag in the arguments.
 
## [1.1.2] - 2020-02-20
### Updated
- Fixed node-selector feature for aws.

## [1.1.1] - 2020-02-04
### Updated
- Fix tag for telegraf metrics #156

## [1.1.0] - 2020-01-31
### Updated
- Rollback to InfluxDB v1.0 support
- telegraf updated to 1.13.2-alpine

## [1.0.14] - 2020-01-15
### Updated
- Fix Telegraf docker image vars

## [1.0.13] - 2020-01-15
### Updated
- Autonity to  dev-0.3.0-fix2
- Add Telegraf and IndluxDB support

## [1.0.12] - 2020-01-10
### Updated
- Fix bugs with prometheus metrics

## [1.0.11] - 2020-01-10
### Updated
- Fix bugs with prometheus metrics

## [1.0.10] - 2020-01-02
### Updated
- Fix bug with RPC https service

## [1.0.9] - 2020-01-02
### Updated
- Fix bug with RPC https service

## [1.0.8] - 2019-12-30
### Updated
- Support external LB for public RPC with ip src white list

## [1.0.7] - 2019-12-27
### Updated
- Fix bug with availability zones for persistent volumes

## [1.0.6] - 2019-12-23
### Updated
- Support node label

## [1.0.5] - 2019-12-23
### Updated
- Support static GCP public IP for p2p

## [1.0.4] - 2019-11-15
### Updated
- Autonity update to v0.3.0

## [1.0.3] - 2019-11-15
### Updated
- Workshops update

## [1.0.2] - 2019-11-07
### Updated
- Workshops update

## [1.0.1] - 2019-10-25
### Added
- Persistent storage support

## [1.0.0] - 2019-10-24
### Updated
- Refactoring `validator` => `autonty-node`
- Added helm tests

## [0.0.5] - 2019-10-22
### Updated
- Fixed Notes to get contract address
- Fixed workshop docs

## [0.0.4] - 2019-10-22
### Added
- Workshop to join new node
### Updated
- Workshop for initial ceremony
- Move out genesis.yaml to separated file
- Fixed key error in genesis `governanceOperator` to --> `operator`

## [0.0.3] - 2019-10-21
### Changed
- key in genesis configmap
- NOTES.txt
- updated init-ceremony image to v1.0.0

## [0.0.2] - 2019-10-17
### Added
- Support AWS NodePort for static IP
- Initial ceremony Workshop 

## [0.0.1] - 2019-10-15
### Added
- Essential implementation of initial ceremony
