**Owner:** Ivan Petrenko · **Last reviewed:** 2026-11-24 · **Status:** draft

# Automations and AI use: registry

Every automation and every use of AI at Fernway should have an entry here. One entry per automation, each with a named owner.

Never paste credentials into this file; say which 1Password item holds them instead.

## Entry format

```
### <name>
- Owner:
- Runs in:
- What it does:
- Trigger:
- Systems it touches:
- Where its credentials live (1Password item, never the value):
- What data it sees (customer data? yes / no):
```

---

## n8n workflows

- **Owner:** Ivan Petrenko
- **Runs in:** Ivan's own n8n instance.
- **What they do:** not documented yet: ask Ivan Petrenko. There are six or seven workflows, and nobody else can explain them.
- **⚠️ Known risk:** a couple of them have API keys pasted directly into the nodes instead of 1Password (breaks team rule 4). The keys must be moved into 1Password. Never copy a key into this repo, not even to flag it.

Each workflow needs its own entry below, in the format above.

## Claude for support draft replies

- **Owner:** not named yet.
- **Status:** trial. The team is trying out Claude to draft support replies.
- **Rules for what may be pasted in:** none yet. Undecided: see [open-questions.md, item 4](../open-questions.md#4-what-may-be-pasted-into-claude-for-support-draft-replies).
- **Already in force:** team rule 3 says customer data stays in HubSpot, Stripe and the production database, with no exports into AI tools (`company/team-rules.md`).

## Claude in this repo

- **Owner:** Hana Kim (repo owner)
- **What it does:** answers questions from the files in this repo, following `CLAUDE.md`.
- **What data it sees:** only this repo. No customer data, secrets or compensation are allowed here (see `CONTRIBUTING.md`).

## Claude via @claude in GitHub issues

- **Owner:** Hana Kim (repo owner)
- **Status:** being set up. Live once the Claude GitHub app is installed on this repo and the API key secret is added.
- **Runs in:** GitHub Actions, `.github/workflows/claude.yml` (uses `anthropics/claude-code-action@v1`).
- **What it does:** answers questions in issues and pull requests that mention `@claude`, from the repo's files and following `CLAUDE.md`.
- **Trigger:** `@claude` in an issue title or body, an issue comment, or a PR review or review comment. Only people with write access to the repo can trigger it.
- **Where its credentials live:** GitHub repository secret `ANTHROPIC_API_KEY` (the value is never written in this repo).
- **What data it sees:** this repo, plus the text of the issue or PR it was mentioned in. Don't paste customer data into issues (team rule 3).
