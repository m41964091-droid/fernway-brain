**Owner:** Lukas Weber · **Last reviewed:** 2026-11-24 · **Status:** draft

# New customer onboarding

**Owner:** Lukas Weber (Customer Success), end to end.
**Measured by:** T2L, from contract signed to first schedule published. Typical today: 1–3 days. The pitch is under a day.

## Flow

1. Contract signed in HubSpot.
2. Lukas books a 45-minute setup call.
3. Lukas imports the venue and staff list from the customer's CSV (the importer).
4. Lukas configures pay rules for the country.
5. Customer publishes their first schedule. This is where T2L stops.
6. 7-day check-in call.
7. Handover to support (`processes/support-escalation.md`).

Step-by-step version: `runbooks/01-new-customer-setup.md`.

## Known problems

- **The importer fails** on names with non-Latin characters and on files exported from Apple Numbers. Noor Haddad knows the workaround; it has never been written down, so Lukas messages him every time. See `runbooks/02-importer-failures.md`.
- **"Activation" has no agreed meaning.** Lukas uses it to mean a full week scheduled; sales and Metabase use it differently. See `open-questions.md`, item 2.
