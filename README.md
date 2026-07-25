# LLM Response Evaluation Portfolio

A practical portfolio demonstrating structured evaluation of AI-generated responses for accuracy, safety, relevance, clarity, instruction following, and evidence quality.

The work focuses on transparent reasoning: identifying claims, verifying them against reliable sources, classifying errors by severity, and improving weak responses.

## Featured Case Study

### [Earthquake Safety Guidance](./evaluation_examples.md)

A safety-critical comparison of two AI-generated answers to an earthquake preparedness question.

The case study includes:

- A weighted 100-point evaluation rubric
- Claim-by-claim factual verification
- Critical, major, and minor error classification
- A safety override for potentially harmful advice
- Evidence from authoritative Japanese sources
- A rewritten final answer
- A documented evaluator decision

**Result:** Response A scored **31/100 and failed for unsafe advice**. Response B scored **95/100 and was strongly preferred**.
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
- [ ] Japanese localization and cultural accuracy case study
- [ ] Legal AI hallucination and safety analysis

## Ethics and Confidentiality

All examples in this repository are original portfolio exercises. They do not contain confidential employer information, proprietary guidelines, or real assessment materials.
