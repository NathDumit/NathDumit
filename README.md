# Nathália Dumit

**Data engineer · data, finance and risk** · Rio de Janeiro, Brazil · open to remote roles in the US and Europe · fluent in English

I turn messy, undocumented systems into data pipelines a finance team can trust and act on. Economics and international relations by training, data engineering by practice.

## Selected work

**Currency tooling used daily by a finance team.** Built a tool that computes the value-weighted average exchange rate of the invoices due each day, which the team uses to decide how many dollars to buy. It replaced a manual spreadsheet flow, and it has guardrails against mistyped rates.

**Pipelines that can be trusted.** Orchestration with retries, locks and dependency ordering, a monitor that catches silent failures (stale files, missing columns, row counts that drop without an error), and an automated test suite. Open source: [pipeline-kit](https://github.com/NathDumit/pipeline-kit).

**Reverse engineering undocumented systems.** Reconstructing keys, relationships and business rules of a legacy database from the data alone, under heavy software restrictions.

**Security.** [SolShield](https://github.com/NathDumit/solshield), a wallet-risk checker built at a hackathon. Currently studying cybersecurity and cloud (AWS/Azure).

## Case studies

All of these use synthetic data and show the method, not any employer's data.

| Case | What it shows |
|---|---|
| Revenue intelligence dashboard | YTD vs prior year, pace vs STLY, pickup-based forecast, concentration and cancellation exposure |
| Reverse-engineering a legacy database | Key discovery, foreign-key inclusion tests, cardinality, data-quality traps |
| From file to decision | An orchestrated pipeline with monitoring and tests |
| Weighted exchange rate for treasury | Why a value-weighted average, and the guardrails around bad inputs |

- [Travel revenue intelligence](https://nathdumit.github.io/NathDumit/revenue-intelligence.html)
- [Reverse-engineering a legacy database](https://nathdumit.github.io/NathDumit/legacy-database.html)
- [From file to decision: orchestration, monitoring and tests](https://nathdumit.github.io/NathDumit/pipeline.html)
- [Weighted exchange rate for treasury](https://nathdumit.github.io/NathDumit/weighted-fx-rate.html)

All four use fictional systems and synthetic data. [Index page](https://nathdumit.github.io/NathDumit/).

## How I work

- I treat "the script ran" and "the data is right" as two different claims, and I test for the second.
- I write down what I could not verify, and I fix the tests when the logic changes rather than the other way around.
- I explain technical work to non-technical people. For five years I have volunteered to run **Economia das Minas**, a community of 38 thousand women focused on financial autonomy.

## Stack

Python · pandas · SQL · Power BI · Git and GitHub Actions · pytest · Parquet · AWS and Azure (learning)

## Contact

[LinkedIn](https://www.linkedin.com/in/nathalia-dumit/)
