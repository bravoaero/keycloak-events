# GitHub Actions workflows

This Bravo Aero fork owns the workflows in this directory.

- `ci.yml` builds and tests pushes to `main` and pull requests.
- `release.yml` builds and publishes a GitHub Release when a tag matching
  `v*-bravo.*` is pushed. The tag must match the Maven project version exactly;
  tests are kept in the separate CI workflow so a transient integration-test
  failure cannot create a partially published release.
- The remaining validation workflows were inherited from upstream.
