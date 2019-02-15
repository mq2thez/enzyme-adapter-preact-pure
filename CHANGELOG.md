# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

- Calls to `setState` on fully-rendered components now trigger synchronous
  updates, for consistency with shallow rendering.

## [1.1.0] - 2019-02-14

- Map `class` prop to `className` so that Enzyme class selectors work.

## [1.0.0] - 2019-02-14

- Initial release.