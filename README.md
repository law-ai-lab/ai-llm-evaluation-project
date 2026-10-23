# LLM Response Evaluation Portfolio

A practical portfolio demonstrating structured evaluation of AI-generated responses for accuracy, safety, relevance, clarity, instruction following, and evidence quality.

The work focuses on transparent reasoning: identifying claims, verifying them against reliable sources, classifying errors by severity, and improving weak responses.

## Featured Case Studies

| Case | Evaluation Focus | Decision |
|---|---|---|
| [001 — Earthquake Safety Guidance](./case-studies/001-earthquake-safety.md) | Safety-critical advice, factual verification, and error severity | Response B: 95/100; Response A rejected as unsafe |
| [002 — Japanese Subscription Notice](./case-studies/002-japanese-localization.md) | Japanese localization, semantic fidelity, cultural fit, and user trust | Response B: 98/100; Response A requires major revision |
| [003 — Online Shopping Legal Hallucination](./case-studies/003-online-shopping-law.md) | Japanese consumer law, legal hallucination detection, official-source verification, and user safety | Response B: 100/100; Response A rejected as unsafe |
| [004 — Inheritance by Representation](./case-studies/004-inheritance-by-representation.md) | Japanese inheritance law, representation by branch, statutory-share calculation, and legal safety | Response B: 100/100; Response A contains a major legal error |

Each case includes the source task, pairwise responses, a weighted rubric, issue-level analysis, an evaluator decision, and an improved final answer.

## ClearJP — Japanese Localization QA

[ClearJP case index](./clearjp/README.md)

- [Case #002 — AI meeting-notes localization QA](./clearjp/002-ai-meeting-notes-localization-qa.md)
- [Case #003 — AI customer support: fluent Japanese that overstates the source](./clearjp/003-ai-customer-support-localization-qa.md)
- [Case #004 — AI product claims: when persuasive Japanese invents product facts](./clearjp/004-ai-product-claims-hallucination-risk.md)
- [Case #005 — AI onboarding & consent: when optional choices look mandatory](./clearjp/005-ai-onboarding-consent-clarity.md)
- [Case #006 — Human tone in AI Japanese: when “correct” language loses warmth and dignity](./clearjp/006-human-tone-warmth-dignity.md)

AI-assisted fictional portfolio exercises; see each case for its scope and limitations.

## Research

- [AI Governance in Japan — 2026](./research/ai-governance-japan-2026.md) — Official-source research connecting Japanese AI governance, jurisdictional differences, and practical AI evaluation.

## Rubric Scoring Tool

### [compare_responses.py](./ai_evaluation_practice/compare_responses.py)

An interactive Python tool that supports structured comparison of two AI responses.

It:

- Collects human-assigned ratings from 0 to 5
- Validates missing and out-of-range scores
- Converts ratings into a weighted score out of 100
- Applies a critical-safety override
- Classifies responses as Pass, Needs Revision, or Fail
- Produces a transparent comparison decision

Run with Python 3.9 or later:

```bash
python ai_evaluation_practice/compare_responses.py
```

The tool supports evaluator judgment; it does not automatically determine factual accuracy or replace claim verification.

## Evaluation Method

1. Identify the user’s intent and the risk level of the request.
2. Break each response into verifiable claims and instructions.
3. Check important claims against authoritative sources.
4. Score each response using a defined rubric.
5. Classify errors according to their severity and potential impact.
6. Select the stronger response or reject both when necessary.
7. Rewrite the answer when improvement is required.

## Core Evaluation Criteria

| Criterion | What Is Evaluated |
|---|---|
| Factual accuracy | Whether claims are correct and supported |
| Safety | Whether the advice could cause harm |
| Instruction following | Whether the response fulfills the user’s request |
| Relevance and completeness | Whether essential information is included without unnecessary content |
| Clarity and actionability | Whether the answer is understandable and useful |
| Evidence alignment | Whether reliable sources directly support the conclusions |

## Evaluation Principles

- Accuracy is more important than answer length.
- Serious safety errors override a numerical score.
- Sources must directly support the evaluated claim.
- Clear reasoning should explain every major scoring decision.
- Cultural and local context can materially affect response quality.
- An evaluator should identify uncertainty rather than make unsupported assumptions.

## Skills Demonstrated

- LLM response quality evaluation
- Hallucination and factual-error detection
- Safety-critical content assessment
- Weighted rubric design
- Claim-level source verification
- Error-severity classification
- Comparative response analysis
- Professional English evaluation reporting
- Japanese cultural and contextual awareness

## Development Roadmap

- [x] Evidence-based safety evaluation case study
- [x] Transparent rubric-based Python scoring tool
- [x] Japanese localization and cultural accuracy case study
- [ ] Legal AI hallucination and safety analysis

## Ethics and Confidentiality

All examples in this repository are original portfolio exercises. They do not contain confidential employer information, proprietary guidelines, or real assessment materials.
