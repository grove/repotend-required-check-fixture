# Docs-only path-filter test

This file intentionally changes only `docs/**`.
The `Filtered CI` workflow runs on pull requests changing `src/**`, so this PR should not schedule its `Tests` and `Optional` jobs.

The expected merge-blocking behavior depends on `Tests` being configured as a required status check on `main`.
