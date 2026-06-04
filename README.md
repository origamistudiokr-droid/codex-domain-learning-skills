# Codex Domain Learning Skills

PM and product strategy skills for learning a business, product, or industry domain.

## Included Skills

- `domain-learning`: Main orchestrator that synthesizes the full PM learning guide.
- `stakeholder-map`: Identifies actors, incentives, conflicts, and dependencies.
- `vocabulary-map`: Explains domain terms and industry concepts.
- `money-flow`: Maps revenue, costs, margins, and incentives.
- `metrics-map`: Identifies KPIs and health indicators.
- `constraints-map`: Explains operational, legal, technical, and trust constraints.
- `user-behavior`: Analyzes repeated user psychology and behavior loops.
- `industry-history`: Connects market history to current product patterns.

## Install

In Codex, use `skill-installer` with this GitHub repo:

```text
[$skill-installer] Install these skills from GitHub:
repo: origamistudiokr-droid/codex-domain-learning-skills
paths:
- skills/domain-learning
- skills/stakeholder-map
- skills/vocabulary-map
- skills/money-flow
- skills/metrics-map
- skills/constraints-map
- skills/user-behavior
- skills/industry-history
```

Equivalent installer command:

```bash
python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo origamistudiokr-droid/codex-domain-learning-skills \
  --path \
  skills/domain-learning \
  skills/stakeholder-map \
  skills/vocabulary-map \
  skills/money-flow \
  skills/metrics-map \
  skills/constraints-map \
  skills/user-behavior \
  skills/industry-history
```

After installing, restart Codex or open a new Codex session so the skills can be picked up.

## Example

```text
[$domain-learning] Analyze the Goodoc healthcare app domain from a PM perspective.
```
