# Changelog
All notable changes to this project will be documented in this file.

## [released]

## [1.0.0] - 02/08/2018
### Added
- Built CIS compliant (CIS CentOS Linux 7 Benchmark v2.2.0 - 12-27-2017) Centos 7.5.1804 images for ecs and ec2 instances.
- This image has been security tested using OpenSCAP C2S profiles (both score 95% or above).
- The OS installs are 250 packages or below.

## [1.0.1] - 02/08/2018
### Added
- Maintainer added to README.md

## [1.0.2] - 02/08/2018
### Added
-  CONTRIBUTING.md linked in README.md

## [1.0.3] - 27/09/2018
### Added
- Amended log rotate from 3 to 1 in 090-harden.sh.
- Applied CIS Docker Community Edition Benchmark (v1.1.0 - 07-06-2017) hardening to CentOS7-ecs.json build.
- Added docker-builder to perform alpine container builds for Java Microservices, NodeJS, hashicorp vault and consul.
- Updated README to reflect the above changes/additions.
