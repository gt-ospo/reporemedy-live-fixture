# Disposable RepoRemedy live fixture

Synthetic repository for the repository-context collector in RepoRemedy PR #6.
Do not execute or install this repository. Actions are disabled at repository level.
It contains no real application data or secrets. Tests read only; setup created
settings, a synthetic failed commit status, an unsigned release, an unprotected
environment and inactive webhooks pointing to the reserved example.invalid domain.

The recorded commit is `af64e06b117ad849fb91095ad15d70593042a1fd`. Its README exists and its support text differs
from main. Main deliberately omits README, CONTRIBUTING, SECURITY, CODE_OF_CONDUCT,
LICENSE, CODEOWNERS, CITATION and issue/PR templates. Dependencies and Actions refs
are unpinned; no tests, SAST, dependency updater, fuzzing, SBOM or signing are set up.
The binary artifact, oversized file and symlink exercise collection boundaries.

See FIXTURE-COVERAGE.md for all 68 catalog remedies and the limits of this fixture.
These are candidate audit problems, not fabricated auditor results. RepoRemedy PR #6
collects context; this fixture does not prove any Scorecard score or RepoAuditor result.
Do not modify main or its live settings during a test run. Use separate branches
for future remedy publication tests and update the pinned test contract deliberately.
