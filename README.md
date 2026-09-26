# UniteAndCreateForLife

We build **HAL SUPREME**: an evidence-driven AI engineering and multimodal production system with durable work state, replaceable model and media providers, privacy controls, provenance, and human release gates.

[![Public Portfolio Evidence](https://github.com/UniteAndCreateForLife/HAL_SUPREME/actions/workflows/public-portfolio.yml/badge.svg)](https://github.com/UniteAndCreateForLife/HAL_SUPREME/actions/workflows/public-portfolio.yml)

## New this week

- **[prt-check](https://github.com/UniteAndCreateForLife/prt-check)** is a free check for GitHub's 2026 `pull_request_target` changes.
  - Since July 20, `actions/checkout` refuses fork checkouts in privileged workflows.
  - From Nov 2, the trigger is blocked on public repositories that have no Actions policy allowing it.
  - It runs as one command or one Action step, and gives the line to fix.
  - [Report: what breaks in the 1,000 most-starred repositories](https://github.com/UniteAndCreateForLife/prt-check/blob/main/REPORT.md).
- **[Verified fix](https://github.com/UniteAndCreateForLife/HAL_SUPREME/blob/main/docs/WORK_WITH_HAL.md#fixed-price-offer-verified-fix)** is one sandbox-verified pull request for one GitHub issue, and you pay only if you merge. So far it has 4 merged PRs, each verified on a clean checkout: [#49](https://github.com/UniteAndCreateForLife/HAL_SUPREME/pull/49), [#50](https://github.com/UniteAndCreateForLife/HAL_SUPREME/pull/50), [OPI #9](https://github.com/UniteAndCreateForLife/HAL_OPEN_PUBLIC_INTEREST/pull/9), [OPI #10](https://github.com/UniteAndCreateForLife/HAL_OPEN_PUBLIC_INTEREST/pull/10).
- **[Bait for AI coding agents](https://github.com/UniteAndCreateForLife/HAL_SUPREME/blob/main/case-studies/AI_AGENT_BOUNTY_HONEYPOT_GUARD_2026-09-24.md)**: bounty repositories that ask agents to paste their system prompt, plus the open detector that caught 183 of 184 such issues with no false positives on 14 widely used repositories. [Try it in the browser](https://huggingface.co/spaces/uniteandcreateforlife/agent-bounty-guard).

## Start here

- **[Public engineering portfolio](https://github.com/UniteAndCreateForLife/HAL_SUPREME/blob/main/PORTFOLIO.md)** — selected work, capabilities, and evidence links
- **[HAL SUPREME](https://github.com/UniteAndCreateForLife/HAL_SUPREME)** — curated public source, tests, integrations, and demos
- **[Public work log](https://github.com/UniteAndCreateForLife/HAL_SUPREME/blob/main/docs/PUBLIC_WORK_LOG.md)** — dated, reviewable outcomes
- **[Community hub](https://github.com/UniteAndCreateForLife/hal-supreme-community)** — peer join, MCP setup, agent card, and model-gateway example
- **[Public-interest package](https://github.com/UniteAndCreateForLife/HAL_OPEN_PUBLIC_INTEREST)** — provenance, scope, budget, privacy, security, and release-readiness materials

## Current verified work

### ChatGPT + Livepeer Creative MCP

A read-only inventory on 2026-09-24 verified **125 callable MCP methods** and **209 available capabilities** across AI generation and production tooling. The public integration discovers current schemas at runtime, keeps credentials out of RPC bodies and Git, and requires explicit review before generation or spend.

[Read the case study](https://github.com/UniteAndCreateForLife/HAL_SUPREME/blob/main/case-studies/LIVEPEER_CHATGPT_MCP_2026-09-24.md) · [Download v0.1.0](https://github.com/UniteAndCreateForLife/HAL_SUPREME/releases/tag/livepeer-creative-mcp-v0.1.0) · [Inspect the plugin source](https://github.com/UniteAndCreateForLife/HAL_SUPREME/tree/main/plugins/livepeer-creative-mcp) · [Open the machine receipt](https://github.com/UniteAndCreateForLife/HAL_SUPREME/blob/main/evidence/portfolio/livepeer_chatgpt_mcp_2026-09-24.json)

### HAL Campus Evidence Desk

A synthetic-data campus operations and research-review prototype with evidence citations, deterministic acceptance, privacy egress checks, tenant-scoped RBAC, and a tamper-evident review chain. The current public suite contains **30 tests**. Its committed benchmark processed **30,000 reports** with zero acceptance-invariant failures and no paid compute.

[Inspect the project](https://github.com/UniteAndCreateForLife/HAL_SUPREME/tree/main/challenges/global-smart-campus-2026) · [Try the public demo](https://hal-campus-evidence-desk.therealjakobhedrich.workers.dev) · [Open the judge receipt](https://github.com/UniteAndCreateForLife/HAL_SUPREME/blob/main/challenges/global-smart-campus-2026/JUDGE_VERIFICATION_RECEIPT.json)

## What this work demonstrates

- durable agent and workflow architecture;
- MCP, model, media, and compute-provider integration;
- video, image, audio, 3D, assembly, quality control, and provenance workflows;
- privacy minimization, RBAC, tenant isolation, tamper detection, and fail-closed routing;
- Python services and CLIs, Cloudflare Workers, Docker, GitHub Actions, and multi-platform CI;
- clear separation between configured, tested, privately verified, and publicly released states.

## Collaboration

We are building relationships with infrastructure providers, media and model platforms, research partners, grant programs, accelerators, and investors. The portfolio emphasizes inspectable implementation evidence, current limitations, and reproducible verification.

Public work is sanitized before publication. Credentials, personal data, private connector paths, account state, generated private media, and unsupported production claims are excluded.
