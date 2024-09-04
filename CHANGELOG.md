<!--
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Added      - for new features.
Changed    - for changes in existing functionality.
Deprecated - for soon-to-be removed features.
Removed    - for now removed features.
Fixed      - for any bug fixes.
Security   - in case of vulnerabilities.
-->

## [v6.0.0] - 2024-09-01

### Changed

- Update the way we extract the changelog, this should fix auto-changelog

## [v5.0.0] - 2024-09-01

### Changed

- Updated the build and release workflow to include changelog

## [v4.0.0] - 2024-09-01

### Added

- Nothing, this is just a test

## [v3.0.0] - 2024-09-01

### Added

- Nothing, this is just a test

## [v2.0.0] - 2024-09-01

### Added

- Nothing, this is just a test

## [v1.0.0] - 2024-09-01

### Added

- Added support for OAuth 2.0 for user authentication.
- New admin dashboard with analytics for better insights.
- Added API endpoints for managing user profiles.
- Implemented lazy loading for images to improve page load times.

### Changed

- Updated UI to a new design system for more consistent styling.
- Database schema changes to optimize query performance.
- Upgraded React from v17 to v18.
- Refactored backend routing for better code maintainability.

### Deprecated

- Deprecated `GET /api/v1/user-details`, use `GET /api/v2/user` instead.

### Removed

- Removed support for Internet Explorer 11.
- Old authentication endpoints `/auth/login`, `/auth/register` removed in favor of new OAuth 2.0 flow.

### Fixed

- Fixed bug with file upload in Safari where progress was not displayed correctly.
- Fixed caching issue in the service worker that caused incorrect data rendering.
- Res

### Security

- Update dependency X which implemented a vulnerability
