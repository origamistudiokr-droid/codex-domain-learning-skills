---
name: korean-bimun-editor
description: Use when Codex needs to review, diagnose, or revise Korean text for 비문, awkward collocations, translationese, unnatural product/landing-page copy, unclear subject-object relationships, overly forced metaphors, or Korean copy that should sound natural to native Korean readers. Trigger for Korean requests such as "비문 첨삭", "문장이 어색해", "한국인이 이해하기 어렵다", "카피 자연스럽게", "번역투 고쳐줘", "표현 분석", or "프롬프트 작성".
---

# Korean Bimun Editor

## Core Task

Revise Korean text so it reads naturally to native Korean readers while preserving the user's intent, audience, and tone. Separate true grammatical errors from merely awkward or over-stylized copy, then provide practical rewrites.

## Workflow

1. Identify the text's job: landing-page headline, body copy, product UI, ad copy, explanation, prompt, or general prose.
2. Infer the audience and tone from the user request. If missing, default to clear, contemporary Korean with minimal exaggeration.
3. Diagnose each suspicious phrase before rewriting:
   - **비문**: grammar, agreement, omitted subject/object, broken modifier relationship, or sentence structure that blocks comprehension.
   - **어색한 결합**: words are grammatical but do not naturally pair in Korean, such as unnatural verb-object or adjective-noun combinations.
   - **번역투**: foreign-language structure, abstract nouns, or literal metaphors that make Korean feel stiff.
   - **과한 은유**: stylish but unclear expressions that require interpretation before persuasion.
   - **톤 문제**: too childish, too formal, guilt-inducing, exaggerated, or off-brand.
4. Rewrite with Korean-native collocations first, then adjust rhythm and brand tone.
5. Explain the key edit briefly. Do not over-explain every particle unless the user asks.

## Revision Principles

- Prefer concrete Korean verbs: `도착하다`, `받다`, `앞에 두다`, `줄이다`, `가라앉히다`, `느끼다`, `도움이 되다`.
- Avoid awkward abstract pairings unless the brand intentionally uses them and the user approves.
- Preserve the persuasive logic. For product copy, do not polish away the causal chain.
- Do not blame the user. Convert shame-based copy into situational or behavioral framing.
- Avoid guarantees in health, weight, finance, or legal contexts. Use cautious wording such as `도움이 됩니다`, `쉬워져요`, `느껴질 수 있어요`.
- Keep Korean landing-page copy short enough to scan. Split long reasoning into headline plus supporting sentence.
- When a phrase is not strictly ungrammatical but feels unnatural, say so: `문법 오류라기보다 어색한 결합입니다.`

## Output Patterns

For analysis-only requests, use this format:

```text
문제 표현: ...
진단: 비문 / 어색한 결합 / 번역투 / 과한 은유 / 톤 문제
왜 어색한가: ...
자연스러운 대안:
1. ...
2. ...
추천: ...
```

For rewrite requests, provide 2-3 alternatives when wording materially affects tone:

```text
대안 1: ...
대안 2: ...
대안 3: ...
추천: ...
이유: ...
```

For file-editing requests, edit the text directly and summarize:

```text
수정한 카피:
- 이전: ...
- 이후: ...

검토:
- 비문/어색한 결합 제거
- 의도와 톤 유지
```

## Useful Heuristics

- `마주하다` pairs naturally with `현실`, `문제`, `상황`, or people. For food or objects, prefer `도착하다`, `받다`, `앞에 두다`, `펼쳐두다`.
- `켜다` pairs naturally with lights, devices, functions, or modes. For feelings or bodily sensations, prefer `느끼다`, `생기다`, `가라앉다`, `줄어들다`.
- `붙잡다` pairs naturally with people, opportunities, 마음, 정신, or 흔들리는 감정. For willpower, prefer `의지로 버티다`, `참다`, `마음을 다잡다`, `유지하다`.
- If a headline uses a metaphor, the next line must make the literal meaning obvious.
- For Korean product copy, a natural sentence is often better than a clever sentence.

## Examples

Awkward:

```text
의지는 붙잡기 어렵지만, 포만감은 먼저 만들 수 있어요.
```

Better:

```text
배고플 때 의지로 참는 건 쉽지 않아요.
먹기 전 물 한 잔으로 허기를 먼저 낮춰요.
```

Awkward:

```text
바쁜 하루 끝에 배달음식을 마주하면...
```

Better:

```text
야근 끝에 배달음식이 도착하면...
배달음식을 앞에 두면...
```
