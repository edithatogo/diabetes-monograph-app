# Contributing to diabetes-monograph-app

This repository contains the diabetes monograph SMART application. Its [README](README.md) marks it deprecated and not actively maintained. Keep that status clear when proposing maintenance, documentation, or compatibility changes.

## Before you start

Search existing issues and pull requests before starting, and discuss substantial changes or new dependencies in an issue. Use an issue template when one is offered. For a bug, include the affected commit or version, environment, a minimal reproduction, and expected versus observed behavior; remove sensitive information from logs and screenshots.

## Development and validation

Review [package.json](package.json), [index.html](index.html), and [launch.html](launch.html) to identify the affected integration points. The package manifest lists a FHIR client dependency but does not define npm build, test, or serve scripts. Do not report those scripts as available; document a compatible local preview or focused check used for your change.

Use synthetic patient resources and shareable examples. Check the changed launch flow, data mapping, missing-data behavior, terminology, and rendered monograph as appropriate. If clinical statements or calculations change, provide their sources and distinguish content review from software execution evidence. Keep legacy compatibility changes focused, preserve third-party notices, and report untested browser or dependency combinations explicitly.

## Pull requests

Work on a focused branch from the current default branch. Open a pull request explaining the problem, the resulting behavior, and any compatibility or data-format changes. Link the relevant issue and complete any existing PR template.

Add focused regression coverage for changed behavior and update affected examples or documentation. Describe the checks actually run, their results, and any checks you could not run. For documentation-only changes, verify links, examples, and rendered formatting. Use the repository's existing checks and review/merge process; preserve required checks and resolve actionable feedback without weakening the checks.

## Security and sensitive information

Follow the [account security policy](https://github.com/edithatogo/.github/blob/main/SECURITY.md). Report vulnerabilities privately through the repository's **Report a vulnerability** option if available; otherwise request a private reporting contact without posting exploit details. Never include credentials, personal information, restricted datasets, or confidential records in issues, commits, fixtures, or diagnostic output.

## Licensing and conduct

The repository's [license](LICENSE) continues to apply. Be respectful and constructive, and follow the [account code of conduct](https://github.com/edithatogo/.github/blob/main/CODE_OF_CONDUCT.md). Preserve attribution and third-party notices. Contribute only material you are entitled to share; resolve unclear permissions before adding third-party content. This guide does not change licensing terms or introduce a CLA or DCO requirement.

## References

- [GitHub contribution guideline conventions](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)
- [OpenSSF contribution and quality criteria](https://www.bestpractices.dev/en/criteria)
