# GitHub Actions workflows

This Bravo Aero fork owns the workflows in this directory.

- `ci.yml` builds and tests pushes to `main` and pull requests.
- `release.yml` builds, tests, and publishes a GitHub Release when a tag matching
  `v*-bravo.*` is pushed. The tag must match the Maven project version exactly.
- The remaining validation workflows were inherited from upstream.
