# Felipe Bentes

Forward-deployed AI engineer. I put AI systems into the daily operations of real small businesses — WhatsApp, phone, payments, CRMs — and then keep them safe, observable, and honestly measured. The model is rarely the hard part. The review gate, the 2 a.m. failure mode, and the operator who has to trust the output are.

## Deployed

**Legal-document automation for a traffic-fine defense law firm (Brazil).** WhatsApp intake → OCR → retrieval → drafted defense → human review console, multi-tenant. Reviewers work in it daily. The deployment is configured so that every generated legal document requires human approval before delivery (the auto-deliver threshold is set above the maximum reachable score), and citations are verified-only and fail-closed. Four production incidents are documented with a write-up and a resolution each — including a cross-border messaging block, resolved by moving the messaging infrastructure into the client's own Business Manager with a runbook in their own language.

**Copilot enablement at WSP.** Delivered an AI workshop to 170+ professionals (March 2026); the national manager asked for a rollout to a further ~50. Automated a weekly reporting task from 2.5 hours to 7 minutes. Those figures are self-reported from my own record, not independently audited.

**Site and CRM for a mobile car-detailing business** (anonymized — no consent on file to name it). Live site plus an automated lead pipeline into their CRM, wiring verified end to end on 2026-06-22.

## Runnable

**[AI Receptionist Lab](https://github.com/founder-felipe/ai-receptionist-lab)** — a voice receptionist with calendar booking, built around a barbershop's workflow. Clone it and run `make demo`; the test suite runs with zero credentials. Live integration against a real calendar was verified on 2026-08-21, and two bugs that only appear when running live — date resolution and a transient auth failure — are fixed in the configuration here. Honesty status: no production callers, no pilots, no revenue.

Two more extracts are being prepared and are not published yet: a policy-safe customer-reactivation engine (typed hard stops, exit-code contract, no model in the decision path) and an autonomous error-remediation loop with a graduated autonomy policy and dual kill switches. Their production run ledger is written up in the case studies.

## Case studies

**[AI deployment case studies]({{REPO_B_URL}})** — architecture, safety choices, incidents, and what I would do differently. Every number carries a class: measured, verified, designed-not-measured, or unknown. Business outcomes I have not measured — legal win rates, revenue, ROI — are marked unknown rather than implied.

## Contact

LinkedIn: [felipe-bentes-ai](https://linkedin.com/in/felipe-bentes-ai) · [therise.ai](https://therise.ai)
