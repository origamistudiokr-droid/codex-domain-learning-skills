---
name: constraints-map
description: Use when Codex needs to analyze operational, legal, regulatory, technical, cost, trust, safety, compliance, logistics, or organizational constraints in a business/product domain, including Korean requests such as "운영 제약", "법적 제약", "기술 제약", "왜 UX가 복잡한가", or "constraints map". Explain how real-world limits shape product decisions.
---

# Constraints Map

## Overview

Analyze the real-world limits that shape a product. The core idea: products are not made from ideal UX alone; they are shaped by law, operations, cost, risk, technology, and organizational capacity.

## Workflow

1. Identify the domain, geography, user type, and product model.
2. List likely constraints across legal, operational, technical, cost, trust, supply, and organizational categories.
3. Explain how each constraint appears in the user experience or product architecture.
4. Distinguish hard constraints from negotiable constraints.
5. Translate constraints into PM tradeoffs, discovery questions, and risk mitigations.
6. For current legal or regulatory claims, verify with up-to-date sources when browsing is available and state the jurisdiction.

## Output Structure

Use this structure:

1. Constraint Overview
   - Name the constraints most likely to shape the domain.
   - State geography and assumptions.

2. Constraint Table
   - Constraint
   - Category: legal, operational, technical, cost, trust/safety, supply, organizational
   - Why it exists
   - How users experience it
   - Product tradeoff
   - Possible mitigation

3. Hard vs Soft Constraints
   - Hard constraints: cannot be ignored without legal, safety, or business failure.
   - Soft constraints: can be improved by process, tooling, design, partnerships, or sequencing.

4. PM Implications
   - UX compromises to expect
   - Engineering or operations dependencies
   - Risks to test early
   - Questions for legal, ops, data, security, or finance

## Constraint Categories

- Legal and regulatory: identity checks, consent, licensing, data retention, audits, accessibility, age limits.
- Operational: manual review, support load, logistics, staffing, training, SLAs, incident response.
- Technical: latency, integrations, data quality, security, scalability, device or network limits.
- Cost: cloud spend, fulfillment, incentives, fraud, human labor, customer acquisition, returns.
- Trust and safety: abuse, fraud, moderation, privacy, reputation, dispute handling.
- Supply-side: inventory, provider availability, geographic density, partner reliability.
- Organization: sales cycle, procurement, compliance approval, legacy systems, internal ownership.

## Quality Bar

- Explain why a product pattern exists instead of labeling it bad UX too quickly.
- Show how constraints create tradeoffs between convenience, trust, cost, and speed.
- Do not provide legal advice; identify issues and suggest consulting qualified experts for binding interpretation.
- Mark uncertain claims and jurisdiction-specific assumptions.
- If the user writes in Korean, answer in natural Korean unless they request another language.
