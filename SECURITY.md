# Security Policy

This policy applies to every repository in the [ai-automation-tools](https://github.com/ai-automation-tools)
organization that does not publish its own `SECURITY.md`.

## Reporting a vulnerability

**Please do not open a public issue for a security problem.**

Report it privately through **[GitHub Security Advisories](https://docs.github.com/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability)** —
open the affected repository, go to the **Security** tab, and choose *Report a vulnerability*. That
keeps the report private until a fix exists.

If private reporting is unavailable on the repository, email **admin@ai-automation-tools.dev**.

Useful things to include, as far as you have them: which repository and version, what an attacker
can achieve, and the smallest set of steps that shows it. A proof-of-concept helps but is not
required — a clear description of the flaw is enough to start.

## What to expect

These are small, self-hosted tools maintained by one person, so this is a best-effort process
rather than a commercial SLA:

| | |
|:---|:---|
| **Acknowledgement** | Within about a week |
| **Assessment** | We will tell you whether we consider it a vulnerability, and why |
| **Fix** | Prioritised by severity and by how exposed the affected code actually is |
| **Credit** | Offered in the advisory or release notes unless you would rather stay anonymous |

If we decide something is not a vulnerability we will say so plainly and explain the reasoning,
rather than letting the report go quiet.

## Scope

**In scope** — anything in the source of these repositories: the tools themselves, their build and
release workflows, and their dependency manifests.

**Out of scope:**

- **Vulnerabilities in third-party dependencies** without a demonstrated exploit path through this
  code. Dependabot alerts are monitored separately; a bare advisory ID is not a report.
- **Findings that require an attacker to already have local access** to the machine running the
  tool. Most of these tools are local-first by design and deliberately trust the local user — that
  trust boundary is the architecture, not a bug.
- Automated scanner output with no analysis attached.
- Missing hardening headers or similar findings on the static sites under
  `ai-automation-tools.dev`, which serve no user data and hold no session.

## A note on the local-first design

Most of these tools run entirely on the user's own machine and intentionally have no authentication
layer, because the only principal is the person at the keyboard. Reports that treat "no auth on a
`127.0.0.1` listener" as a finding in itself will usually be closed as by-design — **but a way to
reach one of those listeners from off the machine, or to widen its bind address, is very much in
scope** and worth reporting.
