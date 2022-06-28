# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.0] - 2022-06-28

### Changed

- Update pods resource quotas after production testing and fine-tuning to improve efficiency
- Added `namespace: ingress-nginx` to [values.yaml](chart/values.yaml) as required by [Karavel CLI 0.4](https://github.com/karavel-io/cli/releases/tag/v0.4.0)
- Updated to [v1.2.1](https://github.com/kubernetes/ingress-nginx/releases/tag/controller-v1.2.1)

## [1.0.0] - 2022-03-22

Initial release

[unreleased]: https://github.com/karavel-io/platform-component-ingress-nginx/compare/1.0.0...HEAD
[1.1.0]: https://github.com/karavel-io/platform-component-ingress-nginx/compare/1.0.0...1.1.0
[1.0.0]: https://github.com/karavel-io/platform-component-ingress-nginx/releases/tag/1.0.0
