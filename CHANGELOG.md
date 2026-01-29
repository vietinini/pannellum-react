# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3.6] - 2026-01-27

### Changed
- Upgraded React development dependency from 18.1.0 to 17.0.2 for better compatibility
- Upgraded React DOM development dependency from 18.1.0 to 17.0.2
- Replaced `enzyme-adapter-react-16` with `@wojtekmaj/enzyme-adapter-react-17` (v0.8.0)
- Updated Enzyme from 3.3.0 to 3.11.0
- Updated ESLint from 5.8.0 to 7.32.0
- Updated babel-eslint from 10.0.1 to 10.1.0
- Updated eslint-plugin-jsx-a11y from 6.1.2 to 6.5.1
- Updated eslint-plugin-react from 7.11.1 to 7.28.0
- Updated gh-pages from 1.2.0 to 3.2.3
- Updated test files to use React 17 Enzyme adapter
  - `tests/index.test.js`
  - `tests/handlers.test.js`

### Fixed
- Resolved React 17 compatibility issues
- Updated README.md to reflect proper React version support (16, 17, and 18)

### Removed
- Removed warning about React 18 compatibility issues from README.md
