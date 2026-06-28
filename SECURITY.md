# Security Policy

## Integrity of this library

This repository is a **read-only distribution library**. It is public so that anyone can download and
verify its contents, but it is maintained by a single owner:

- **Only the repository owner can push.** There are no write collaborators. Every change to `main` is a
  **GPG-signed commit** authored by the owner — look for the green **Verified** badge on each commit.
- **History is protected.** A branch ruleset on `main` requires signed commits and blocks force-pushes and
  branch deletion, so the published history cannot be silently rewritten.
- **No automation can write here.** GitHub Actions is disabled, and no token or bot has write access.
- **URL permanence** is governed by [`PERMANENCE-POLICY.md`](./PERMANENCE-POLICY.md).

If you download a file, you can confirm it is authentic by checking that the commit that introduced it is
signed and verified under the CRAFTFramework account.

## Reporting a concern

If you believe you have found a security or integrity problem with this repository — for example, a file
that appears to have been renamed, deleted, or altered outside the policy above — please **open a public
issue** on this repository, or contact the maintainer via the details at **craftframework.ai**.

Please do not use this channel for questions about cookbook *content* — those belong on craftframework.ai.

## Scope

This policy concerns the integrity and availability of the files distributed from this repository. It does
not cover GitHub's own platform security, membership, or licensing (see `craftframework.ai/terms`).
