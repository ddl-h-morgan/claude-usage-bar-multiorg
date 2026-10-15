# ClaudeUsageBar (multi-org build)

An unofficial macOS menu-bar app showing claude.ai usage, adapted from
[Artzainnn/ClaudeUsageBar](https://github.com/Artzainnn/ClaudeUsageBar) (MIT) to track every
organization an account belongs to (personal, Team, Enterprise) instead of just one.

- One section per org, labelled with its plan.
- On Team/Enterprise, extra usage shows your own spend and the shared org budget separately.
- Per-org errors are shown instead of failing silently.

Background: [Artzainnn/ClaudeUsageBar#119](https://github.com/Artzainnn/ClaudeUsageBar/issues/119).

## Status

Personal project, provided as-is. It relies on claude.ai's unofficial web API and a pasted
session cookie, so it can break at any time. **This repository does not accept pull requests**;
please send fixes to the upstream project instead.

The CI workflow builds an ad-hoc-signed app and runs only on pushes to `main` and manual dispatch.
