# Codex PM and Korean Editing Skills

Codex skills for PM domain learning and natural Korean copy editing.

## Included Skills

- `domain-learning`: Main orchestrator that synthesizes the full PM learning guide.
- `stakeholder-map`: Identifies actors, incentives, conflicts, and dependencies.
- `vocabulary-map`: Explains domain terms and industry concepts.
- `money-flow`: Maps revenue, costs, margins, and incentives.
- `metrics-map`: Identifies KPIs and health indicators.
- `constraints-map`: Explains operational, legal, technical, and trust constraints.
- `user-behavior`: Analyzes repeated user psychology and behavior loops.
- `industry-history`: Connects market history to current product patterns.
- `korean-bimun-editor`: Reviews and rewrites Korean text for awkward phrasing, translationese, and unnatural copy.

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
- skills/korean-bimun-editor
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
  skills/industry-history \
  skills/korean-bimun-editor
```

After installing, restart Codex or open a new Codex session so the skills can be picked up.

## Example

```text
[$domain-learning] Analyze the Goodoc healthcare app domain from a PM perspective.
```

```text
[$korean-bimun-editor] 이 랜딩페이지 카피가 한국어로 자연스러운지 봐줘.
```
