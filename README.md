# Tshepiso Jafta

**Law-trained legal engineer in Johannesburg.** BA Law (Wits), nearly four years in a Justice's chambers at South Africa's Constitutional Court, now building the tooling that legal teams usually only get to specify: AI document pipelines, workflow design, and the evaluation harnesses that keep both honest.

My working rule: **accuracy is measured, not asserted.** Every AI claim in my projects traces to a committed, reproducible benchmark.

## Flagship work

| Project | What it is | Proof |
|---|---|---|
| **[LexFlow](https://github.com/TshepisoJafta/LexFlow)** | Voice-to-billing platform for legal professionals: WhatsApp or web dictation to reviewable billing entries, with confidence-based escalation to human review. FastAPI, React, Gemini, Supabase. | [Live demo](https://lexflow-rho.vercel.app), 65 tests, CI green |
| **[LexFlow Evals](https://github.com/TshepisoJafta/LexFlow/tree/main/evals)** | Published extraction benchmark built on a South African scheme of arrangement (s114, Companies Act 71 of 2008) and a US merger agreement. Measures the failure mode that matters: does the model invent values that are not in the clause? | Latest run: 96% clause classification, 100% field extraction, **0% hallucinations** across 166 null-field checks |
| **[Nimbus](https://github.com/TshepisoJafta/Nimbus)** | Legal ops portfolio: Power BI KPI dashboard (matter cycle time, contract turnaround, spend vs revenue) and five interactive workflow blueprints with owners, SLAs and failure modes. | [Live](https://nimbus-legal-workflows.vercel.app) |
| **[Dedukto](https://github.com/TshepisoJafta/Dedukto)** | Multi-country payroll calculation engine (SA, UK, US) with an MCP server exposing SARS PAYE/UIF/SDL as callable tools for AI agents. | Pure-function tax engine, tested |
| **[Atlas](https://github.com/TshepisoJafta/Atlas)** | Payroll ops platform across 6 jurisdictions: 17 Supabase tables, 3 Python microservices, self-hosted n8n automation, Next.js dashboard. | Production-grade architecture |

## How I work with AI on documents

Grounding before generation. "Not present" is a first-class answer. Confidence thresholds route uncertain output to human review instead of into the record. Golden sets turn accuracy claims into numbers. Every pipeline keeps an audit trail of what the model saw, what it produced, and who approved it.

## Stack

Python · FastAPI · TypeScript / React · Supabase (Postgres + RLS) · Google Gemini & Anthropic APIs · LangGraph · LanceDB · n8n · Power BI · GitHub Actions

## Contact

[LinkedIn](https://www.linkedin.com/in/tshepisojafta/) · tshepisojafta15@gmail.com
