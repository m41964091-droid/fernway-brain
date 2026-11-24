**Owner:** Hana Kim · **Last reviewed:** 2026-11-24 · **Status:** draft

# Fernway company brain — start here

## What this repo is

The written-down version of how Fernway works: who owns what, how each process runs, the words we use, and what is still undecided. Today most decisions live in Slack threads and most Notion pages are out of date. This repo is meant to be the one place that stays current.

It does **not** hold customer data, secrets, or compensation. Customer data stays in HubSpot, Stripe and the production database; secrets stay in 1Password. See `CONTRIBUTING.md`.

## How to find things

| If you want… | Look in |
|---|---|
| What Fernway is, pricing, positioning | `company/overview.md` |
| Who is on the team and what they own | `company/team.md` |
| Team rules (no decisions in DMs, Friday freeze…) | `company/team-rules.md` |
| Which tool is for what | `company/tools.md` |
| How a flow works end to end | `processes/` |
| Step-by-step instructions you can follow alone | `runbooks/` |
| What is automated, and where AI is used | `automations/registry.md` |
| A word you don't know | `glossary.md` |
| Something the team hasn't decided | `open-questions.md` |

## Who to ask about what

| Topic | Ask |
|---|---|
| Pricing, discounts, pricing exceptions ("Mara-check"), fundraising, top 5 accounts | Mara Voss (CEO) |
| Product, engineering, releases, internal automations / n8n, anything involving customer data | Ivan Petrenko (CTO) |
| Production incidents, the importer workaround | Noor Haddad (backend lead) |
| Frontend | Tom Bäcker |
| QA, technical support, staging | Ana Silva |
| Sales | Sofia Marchetti (Head of Sales) |
| Demos | Daniel Okafor (Account Executive) |
| Inbound and outbound lead qualification | Priya Raman (SDR) |
| Customer onboarding | Lukas Weber (Customer Success) |
| Marketing | Emma Doyle (part-time, 2 days a week) |
| Billing, invoices, vendor accounts, tooling admin, **this repo** | Hana Kim (Ops lead) |
| First-line customer support | Jonas Berg |
| People / HR | Head of People — open role, not filled |

## How to use it day to day

**Ask Claude in the repo.** Open this repo in Claude Code and ask your question in plain words ("Who handles failed payments?"). Claude answers only from these files and names the file it used. If something isn't written down, it says "Not documented yet — ask [owner]".

**Ask Claude in a GitHub issue.** Open an issue in this repo and mention `@claude` with your question. *(Not set up yet: this needs the Claude GitHub app installed on the repo.)*

**Read the files directly.** Everything is plain Markdown.

## How to propose a change

1. Create a branch.
2. Edit or add the file. Keep the header line (Owner, Last reviewed, Status) at the top.
3. Open a pull request. The doc's owner reviews it.
4. Never push straight to `main`.

If you notice you've answered the same question twice, that answer belongs here as a pull request (team rule 2). Full rules: `CONTRIBUTING.md`.
