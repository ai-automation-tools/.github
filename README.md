# `.github`

Organization-wide defaults for [ai-automation-tools](https://github.com/ai-automation-tools).

**Nothing here is a product.** Two jobs only:

| Path | What it does |
|:---|:---|
| `profile/README.md` | Renders on the org's public page at **github.com/ai-automation-tools**, above the repo list. Editing it changes that page — there is nothing else to deploy |
| `SECURITY.md` | The default security policy, inherited by **every repo in the org that does not ship its own**. `cronsole` and `Agent-chat` have their own and keep them |

## Two things that are easy to get wrong

**This repo has to stay public.** Default community health files and the profile README are only
inherited from a *public* `.github` repo. Flipping it private silently disables both — the exact
class of failure the org has hit repeatedly, where a control turns off and nothing reports it.

**Commit with a noreply address.** Because the repo is public, commit author metadata is public, and
**no file edit can remove an email address from a commit that already carries one** — only changing
the repo's visibility hides it, which breaks the inheritance above. The org's landing-page repo had
to be flipped private for exactly this reason. Configure it before the first commit:

```bash
git config user.email '<id>+<username>@users.noreply.github.com'
```

## What does *not* belong here

**`CODEOWNERS` does not inherit.** It is not a community health file — it must live in each
repository's root, `.github/`, or `docs/`. A `CODEOWNERS` placed here governs only this repo.

Other files GitHub *will* inherit from here if added: `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`,
`SUPPORT.md`, `GOVERNANCE.md`, `FUNDING.yml`, `ISSUE_TEMPLATE/`, `PULL_REQUEST_TEMPLATE.md`.
