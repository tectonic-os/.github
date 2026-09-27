# Contributing

This is the default guide for every tectonic-os repository. A repository with
its own `CONTRIBUTING.md` adds its checks and rules to it.

## Pull requests

- One branch and one pull request hold one feature.
- The pull request title is a typed subject, `<type>(<scope>): <description>`.
  The type is one of `feat`, `fix`, `docs`, `style`, `refactor`, `perf`,
  `test`, `build`, `ci`, `chore` or `revert`. The scope is optional, in
  lowercase letters, digits and hyphens. The description starts lowercase and
  has no trailing period. The title is at most 64 characters, because the
  squash merge appends ` (#<number>)` and the subject on `main` stays within
  72. CI fails a title that breaks these rules.
- A pull request merges by squash after its checks pass.
- Sign off every commit under the
  [Developer Certificate of Origin](https://developercertificate.org/) with
  `git commit -s`.
- The [AI use policy](AI_POLICY.md) says how AI tools may be used.

## Conduct and security

Everyone follows the [code of conduct](CODE_OF_CONDUCT.md). Report a
vulnerability privately to john@johngrant.dev, never in a public issue.
