---
name: metrics-map
description: Use when Codex needs to identify, explain, or prioritize key metrics, KPIs, health indicators, or success/failure signals for a business, product, service, marketplace, SaaS, fintech, commerce, game, or other domain, including Korean requests such as "핵심 지표", "KPI", "어떤 숫자를 봐야 해", or "metrics map". Connect metrics to domain risks, product loops, and PM decisions.
---

# Metrics Map

## Overview

Analyze which numbers determine success and failure in a domain. The key question is: which metric breaking would make the business, user experience, or operating model unsafe?

## Workflow

1. Identify the domain's main value loop and business model.
2. Separate north-star, input, output, quality, guardrail, and operational metrics.
3. Explain why each metric matters and what it diagnoses.
4. Identify metric tensions, such as conversion vs trust or growth vs retention.
5. Translate metrics into PM questions, experiments, and dashboard structure.

## Output Structure

Use this structure:

1. Metric Logic
   - Explain what success means in this domain.
   - Name the value loop the metrics should capture.

2. Metrics Table
   - Metric
   - Type: north-star, input, output, quality, guardrail, or operational
   - What it measures
   - Why it matters
   - What a drop or spike may mean
   - Product levers that affect it

3. Metric Tensions
   - Explain which metrics can move against each other and why.

4. Dashboard Recommendation
   - Suggest a compact first dashboard for a PM.

5. PM Implications
   - Experiments to run
   - Risks to monitor
   - Questions for data, design, engineering, or operations

## Domain Examples

- Commerce: conversion, AOV, repeat purchase, return rate, fulfillment success, contribution margin.
- SaaS: activation, retention, churn, expansion, MRR, NRR, product qualified leads.
- Games: DAU, retention, session length, ARPDAU, economy balance, payer conversion.
- Marketplace: liquidity, match rate, time to match, supply density, transaction frequency, trust incidents.
- Fintech: approval rate, fraud loss, chargeback rate, settlement time, KYC completion, delinquency.

## Quality Bar

- Avoid metric laundry lists. Explain the causal model.
- Separate vanity metrics from decision-grade metrics.
- Include guardrails so optimization does not damage trust, quality, or long-term retention.
- Define formulas when useful, but prioritize interpretation.
- Mark assumptions when company stage, product model, or data availability is unclear.
- If the user writes in Korean, answer in natural Korean unless they request another language.
