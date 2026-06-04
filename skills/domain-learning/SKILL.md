---
name: domain-learning
description: >
  Use when Codex needs to help a user learn a new business, product, or industry domain as a PM or product strategist, including Korean requests such as "도메인 학습", "이 업계 이해", "PM 관점으로 분석", or "서비스 도메인 공부". Analyze the domain through seven lenses: stakeholders, vocabulary, money flow, metrics, operational constraints, user behavior patterns, and industry structure/history; synthesize them into one coherent PM learning guide.
---

# Domain Learning

## Overview

Use this skill to teach a domain as a PM would learn it: who participates, what words they use, how money moves, what numbers matter, what constraints shape the product, how users behave, and why the industry became this way.

When specialized skills are available, use them as sub-lenses:

1. `$stakeholder-map`
2. `$vocabulary-map`
3. `$money-flow`
4. `$metrics-map`
5. `$constraints-map`
6. `$user-behavior`
7. `$industry-history`

## Workflow

1. Identify the target domain, geography, business model, and user type from the prompt.
2. If the domain is missing, ask one short clarifying question. Otherwise proceed and state assumptions.
3. Analyze all seven lenses, keeping the depth appropriate to the user's level.
4. Before writing the answer, identify domain terms, English acronyms, Chinese-derived Korean terms, and industry jargon that a beginner may not know. On first use, explain each term in plain everyday language before or alongside the technical term.
5. For business, policy, medical, legal, or operational terms, define the term as a relationship, not as a standalone dictionary meaning: who does what, who pays whom, who decides, when it happens, and why it matters for the product/business.
6. Write difficult term definitions as 2-3 short active sentences instead of one compressed sentence. Avoid abstract noun piles such as "burden structure", "institutional framework", or "entry pathway" unless immediately unpacked into actors and actions.
7. Explain relationships between lenses, not isolated lists. For example: money flow changes incentives, incentives affect metrics, metrics create product tradeoffs.
8. For current regulations, market structure, pricing, or recent industry changes, verify with up-to-date sources when browsing is available and cite source dates.
9. Synthesize into a PM learning guide that helps the user reason about product decisions in the domain.

## Output Structure

Use this structure unless the user asks for a narrower answer:

1. Domain Snapshot
   - Define the domain in plain language.
   - Use plain-language-first phrasing: explain the object or process in everyday Korean first, then add the technical term in parentheses only if useful.
   - Do not require the reader to wait until the Vocabulary section to understand terms used in the snapshot.
   - Name the typical product forms and business models.
   - State key assumptions and geography if relevant.

2. Seven-Lens Analysis
   - Stakeholders: who participates, what each actor wants, and where goals conflict.
   - Vocabulary: the terms that reveal how the industry thinks. Define each term with the likely beginner follow-up questions answered: who uses it, who decides, who pays whom, when it happens, and why it matters.
   - Money Flow: who pays, who earns, who bears cost, and what product behavior drives revenue.
   - Metrics: which numbers signal success, failure, liquidity, risk, or health.
   - Constraints: legal, technical, operational, cost, trust, and supply-side limits.
   - User Behavior: repeated emotions, motivations, avoidance patterns, and behavior loops.
   - Industry History: the market, policy, technology, or cultural reasons current patterns exist.

3. PM Implications
   - Translate the analysis into product decisions, UX tradeoffs, roadmap priorities, and discovery questions.

4. Learning Path
   - Suggest what to study first, second, and third.
   - Include practical exercises the user can apply to a real product or idea.

## Quality Bar

- Prioritize causal structure over trivia.
- Define jargon before using it heavily.
- Assume the reader is smart but new to the domain. Avoid unexplained jargon, acronyms, and Chinese-derived technical terms.
- On first use, define jargon inline using this pattern: plain explanation (technical term).
- Do not define jargon only as a label or dictionary meaning. Include the actor chain when relevant: plain meaning + who/whom + when/condition + product implication.
- Prefer short active sentences over compressed noun phrases. If the definition contains vague words like "structure", "system", "framework", "entry", "burden", "coverage", or "reimbursement", rewrite it to say who acts, who pays, who receives money, and who decides.
- For payment or policy terms, use this definition shape when useful: "Term: simple meaning. Who pays whom or who decides. What changes for the product, user, or business."
- If a term is essential but difficult, include a brief "In plain Korean" explanation before using it repeatedly.
- Run a final jargon scan: any term a first-time PM learner may not know must be replaced, explained inline, or added to Vocabulary.
- Highlight tensions: buyer vs user, growth vs trust, liquidity vs quality, regulation vs convenience, automation vs human operation.
- Mark uncertain claims as assumptions.
- Use concrete services or examples when helpful, but do not let examples replace the domain model.
- If the user writes in Korean, answer in natural Korean unless they request another language.
