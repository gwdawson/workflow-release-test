## How to release the project

### 1. Create a Pull Request (PR)

- In the PR, update the version in the `package.json` file to reflect the new release version.
- Also update the `CHANGELOG.md` file in the same PR. Follow the changelog format outlined below:

### 2. Changelog Format

Ensure the `CHANGELOG.md` follows this structure:

```md
## [v0.0.0] - 2024-09-04

### Added

- ✨ ...

### Changed

- ⚙️ ...

### Deprecated

- ⏳ ...

### Removed

- ❌ ...

### Fixed

- 🐛 ...

### Security

- 🔒 ...
```

### 3. Workflow Trigger

Once the PR is merged, this will trigger the release workflow as defined in the repository:
[GitHub Release Workflow](https://github.com/gwdawson/workflow-release-test/blob/main/.github/workflows/publish-release.yml)

This workflow will handle publishing the new version and any associated release tasks.
