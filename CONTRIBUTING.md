**Owner:** Hana Kim · **Last reviewed:** 2026-11-24 · **Status:** draft

# Contributing to the Fernway brain

These rules apply to everyone who adds to this repo: people and AI tools alike.

## Never write into this repo

- **Secrets or credentials:** passwords, API keys, tokens, shared logins. Secrets live in 1Password (team rule 4). Link to the 1Password item's name if needed, never the value.
- **Customer personal data:** names, phone numbers or emails of people at customer accounts. Customer data stays in HubSpot, Stripe and the production database (team rule 3).
- **Salaries or compensation bands.**
- **Pricing decisions about named accounts** that have not been announced.

If you spot any of these in the repo, tell Hana Kim. Do not copy it elsewhere.

## Every doc has one owner and a review date

Every file starts with this line:

```
**Owner:** <one named person> · **Last reviewed:** YYYY-MM-DD · **Status:** current | draft | outdated
```

- **Owner:** one named person, not a team.
- **Last reviewed:** the date someone last checked the whole doc was still true.
- **Status:** `current` (checked and true), `draft` (not yet confirmed by the owner), `outdated` (known to be wrong, kept until it is fixed).

## When two sources disagree

Don't pick one. Add the disagreement to `open-questions.md`: what each side says, and who decides. When it is decided, update the relevant doc and remove the entry.

## A question answered twice becomes a pull request

This is the team's own rule 2: answer the same question twice and it gets written down. It is also the rule the team breaks most often. If you catch yourself answering something for the second time, open a pull request with the answer.

## How changes land

1. Work on a branch. Never commit straight to `main`.
2. Open a pull request.
3. The doc's owner reviews and approves it. For a new doc, the person who will own it reviews.
4. Update **Last reviewed** on any doc whose content you changed and checked.

## Monthly review

Hana Kim owns this repo. Once a month she lists every doc whose **Last reviewed** date is more than 90 days old and asks each owner to review it or mark it `outdated`.
