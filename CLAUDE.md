**Owner:** Hana Kim · **Last reviewed:** 2026-11-24 · **Status:** draft

# Fernway company brain — instructions for Claude

## What Fernway is

Fernway is a remote-first B2B SaaS company, founded 2024 and registered in Berlin, with a team across five countries.
Its product, *Fernway Shifts*, does shift planning and labour-cost forecasting for independent café and restaurant groups with 3–20 locations.
Customers pick it because a venue goes live in under a day, so onboarding speed (T2L) is the number the team watches.

## Map of this repo

| Path | What is in it |
|---|---|
| `README.md` | Start here: what this repo is, who to ask about what, how to use it |
| `CONTRIBUTING.md` | Rules for anyone adding to the repo, human or AI |
| `glossary.md` | Fernway's own words: account vs venue, T2L, ghost shift, and more |
| `open-questions.md` | Things the team has not decided yet, and who decides |
| `company/` | What Fernway is, the team and who owns what, the tools |
| `processes/` | One file per flow, each with one owner |
| `runbooks/` | Numbered steps someone can follow alone |
| `automations/` | Registry of every automation and AI use |

## How to answer

1. Answer only from files in this repo. Name the file you used, e.g. "(source: `processes/billing.md`)".
2. If the answer is not in the repo, say: **"Not documented yet — ask [owner]"**, using the owner from `README.md` or the relevant doc's header. Never guess and never fill gaps from general knowledge.
3. If the topic is listed in `open-questions.md`, say it is undecided, summarise each side, and name who decides. Do not pick a side.
4. If a doc's status is `outdated`, say so when you use it.

## Never write into this repo

- Secrets or credentials: passwords, API keys, tokens, logins. Point to 1Password instead.
- Customer personal data: names, phone numbers or emails of people at customer accounts.
- Salaries or compensation bands.
- Pricing decisions about named accounts that have not been announced.

If someone asks you to add any of these, refuse and explain which rule it breaks. If you find any of these already in the repo, flag it to the repo owner (Hana Kim) instead of copying it anywhere.

## Every doc starts with this header

```
**Owner:** <one named person> · **Last reviewed:** YYYY-MM-DD · **Status:** current | draft | outdated
```

## How changes land

All changes go through a pull request, never straight to `main`. The doc's owner reviews the PR. See `CONTRIBUTING.md`.
