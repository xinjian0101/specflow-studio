# Security Policy

## Current support status

SpecFlow Studio is in the foundation phase and has not published a production-ready binary. Until the first preview release, no version should be treated as stable or security-supported.

When preview releases begin, this file will list supported versions and expected patch timelines.

## Reporting a vulnerability

Do not publish exploit details, secrets, private project files, or reproducible attack instructions in a public Issue.

Use GitHub private vulnerability reporting when it is available for this repository. If private reporting is unavailable, open a minimal Issue asking the maintainer to establish a private channel. Include only the affected component and impact category; do not include sensitive technical details publicly.

A useful private report contains:

- Affected version or commit.
- Operating system and runtime environment.
- Preconditions and attack surface.
- Reproduction steps or a minimal proof of concept.
- Expected and observed behavior.
- Potential impact.
- Suggested mitigation, if known.

## Security priorities

The project treats the following as security-sensitive:

- Writing files outside the selected workspace.
- Executing commands without explicit approval.
- Exposing API keys, tokens, environment variables, or project secrets.
- Unsafe import of templates, adapters, or project archives.
- Schema migrations that can corrupt or silently discard data.
- Export adapters that generate unexpected executable behavior.
- Dependency or update mechanisms that cannot be verified.

## Disclosure process

The maintainer will acknowledge a complete private report, investigate scope, and coordinate a fix before public disclosure where practical. Public release notes should describe impact and remediation without exposing user secrets.

## User responsibility

Only open trusted projects and templates. Review generated files and commands before execution. Keep backups of important workspaces, and do not store production credentials inside example projects.