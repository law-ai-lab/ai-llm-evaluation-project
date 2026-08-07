# Case Study #004 — Inheritance by Representation and Statutory Shares

## Overview

This case study evaluates two fictional AI responses to a Japanese inheritance-law question involving inheritance by representation. It focuses on heir identification, statutory-share calculation, branch-based reasoning, legal safety, and clear explanation in a high-impact domain.

> **Originality notice:** The prompt, candidate responses, evaluation framework, analysis, and improved answer were created specifically for this portfolio. The names and facts are fictional. The responses do not represent named AI models, real client work, or confidential rating guidelines.

> **Scope notice:** This is an AI-evaluation exercise using general legal information, not legal advice for an individual case.

## Case Summary

| Item | Description |
|---|---|
| Domain | Legal AI / Japanese inheritance law |
| Scenario | A deceased child’s two children inherit by representation |
| Risk level | High impact (legal and financial consequences) |
| Evaluation method | Pairwise response comparison |
| Primary failure mode | Incorrect equal division among individual heirs |
| Selected response | Response B |
| Final scores | Response A: 30/100; Response B: 100/100 |

## Evaluation Prompt

> Keiko dies in Japan without a will. Her spouse died before her. She had two children, Akira and Yumi. Akira died before Keiko and left two children, Hana and Ken. Yumi is still alive. Assume there are no other relevant heirs and nobody has renounced or lost inheritance rights. Who inherits Keiko’s estate, and what are their statutory shares?

## Candidate Responses

### Response A

> Yumi, Hana, and Ken are all Keiko’s descendants, so they inherit equally. Each receives one-third of the estate.

### Response B

> Yumi inherits directly as Keiko’s surviving child. Hana and Ken inherit by representation in place of their deceased father, Akira. Akira’s branch receives the one-half share that he would have inherited, which Hana and Ken divide equally. Therefore, Yumi receives one-half, Hana receives one-quarter, and Ken receives one-quarter. These are the statutory shares; the heirs may agree on a different division.

## Evaluation Framework

Each criterion is rated from 1 to 5 and weighted equally.

| Criterion | What is evaluated | Weight |
|---|---|---:|
| Factual and legal accuracy | Whether the response identifies the heirs and applies the governing rules correctly | 25% |
| Completeness | Whether it explains representation, branch-based division, and every statutory share | 25% |
| Legal safety | Whether it avoids materially incorrect entitlements or misleading certainty | 25% |
| Clarity and actionability | Whether the reasoning and calculations are understandable and usable | 25% |

## Score Summary

| Criterion | Response A | Response B |
|---|---:|---:|
| Factual and legal accuracy | 1/5 | 5/5 |
| Completeness | 2/5 | 5/5 |
| Legal safety | 1/5 | 5/5 |
| Clarity and actionability | 2/5 | 5/5 |
| **Overall score** | **30/100** | **100/100** |

## Issue-Level Analysis

### Response A

#### Major Error — Incorrect individual equal-share calculation

Response A divides the estate equally among Yumi, Hana, and Ken because all three are descendants. This produces the wrong statutory shares.

The calculation must first preserve the two children’s family branches. Yumi’s branch receives one-half. Akira’s branch also receives one-half, and Hana and Ken divide that branch share equally. The correct result is therefore Yumi one-half, Hana one-quarter, and Ken one-quarter.

This is a major legal error because the incorrect shares could directly affect estate distribution and cause legal or financial harm.

#### Missing Legal Reasoning

Response A correctly identifies the three heirs, but it does not explain:

- why Hana and Ken inherit in place of Akira;
- why Akira’s branch retains the share he would have received;
- why Hana and Ken divide only that branch share; or
- that statutory shares do not necessarily dictate the final division if all heirs agree otherwise.

The wording is easy to read, but the central calculation is neither reliable nor safely actionable. A major rewrite is required.

### Response B

#### Correct Heir Identification

Response B correctly identifies Yumi as Keiko’s surviving child and Hana and Ken as heirs by representation in place of Akira.

#### Correct Branch-Based Calculation

It correctly preserves Akira’s one-half branch share and divides it equally between Hana and Ken. The resulting statutory shares—Yumi one-half, Hana one-quarter, and Ken one-quarter—are correct.

#### Appropriate Legal Qualification

The response distinguishes statutory shares from the estate’s final agreed division. This avoids implying that the estate must always be divided in the statutory proportions.

#### Clear Explanation

The response explains who inherits, why each person inherits, and how every share is calculated. No material correction is required.

## Final Decision

**Response B should be selected because it correctly applies inheritance by representation, calculates the statutory shares by family branch, and clearly explains the result.**

Response A should fail because it treats three individual descendants as equal-share heirs and produces materially incorrect statutory shares. Correctly naming the heirs does not compensate for an unsafe distribution calculation in a legal-information setting.

## Improved Answer

> Under the stated assumptions, the statutory shares are Yumi one-half, Hana one-quarter, and Ken one-quarter. Yumi inherits directly as Keiko’s surviving child. Because Akira died before Keiko, Hana and Ken inherit by representation in his place. The two child branches are first treated equally: Yumi’s branch receives one-half, and Akira’s branch receives one-half. Hana and Ken then divide Akira’s branch share equally, so each receives one-quarter. These are the statutory shares, but all heirs may agree on a different division of the estate.

## Source Verification

The legal rules were checked against the following current official Japanese sources on August 7, 2026:

1. [e-Gov — Civil Code, Articles 887, 900, 901, and 907](https://laws.e-gov.go.jp/law/129AC0000000089)
2. [National Tax Agency — Scope of Heirs and Statutory Shares](https://www.nta.go.jp/taxes/shiraberu/taxanswer/sozoku/4132.htm)

Article 887 establishes inheritance by representation when a child dies before the decedent. Articles 900 and 901 govern the statutory shares and the represented branch’s share. Article 907 and the National Tax Agency’s official explanation support the distinction between statutory shares and a different division agreed upon by the heirs.

## Skills Demonstrated

- Japanese inheritance-law evaluation
- Heir identification and statutory-share calculation
- Inheritance-by-representation analysis
- Branch-based legal reasoning
- Major-error and omission classification
- High-impact-domain safety judgment
- Pairwise response scoring
- Official-source verification and source hierarchy
- Clear, qualified answer improvement
