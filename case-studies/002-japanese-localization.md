# Case Study 002: Japanese Localization — Subscription Price Change

## Overview

This case study evaluates two Japanese localizations of an English subscription price-change notice.

The evaluation focuses on whether each response preserves the source facts, communicates the user's options transparently, uses natural Japanese, and fits the tone expected in customer-facing communication in Japan.

> This is an original hypothetical portfolio example. It does not contain confidential employer data or assessment material.

| Item | Details |
|---|---|
| Case ID | 002 |
| Domain | Customer communication / subscription services |
| Locale | Japanese (Japan) |
| Risk level | Medium — financial and user-trust impact |
| Evaluation type | Pairwise localization quality evaluation |
| Final decision | Response B strongly preferred; Response A requires major revision |

---

## Evaluation Task

### English Source

> Starting October 1, 2026, the monthly price for Plus will change from ¥1,200 to ¥1,500 for renewals on or after that date. Your next renewal date appears in Account Settings. If you do not want to continue, cancel before your next renewal; you will keep access until the end of your current paid period. No action is required if you want to continue.

### Localization Instructions

> 日本の顧客向けに、明確で自然な敬語を使ってローカライズしてください。原文の日時・料金・解約条件を正確に保持し、推測による理由や、原文にない強い謝罪を追加しないでください。通知文のみを5文以内で出力してください。

### Response A

> 平素よりPlusをご愛顧いただき、誠にありがとうございます。サービス品質向上のため、2026年10月1日より月額料金を1,200円から1,500円へ改定いたします。継続をご希望でない場合は、アカウント設定から解約できます。多大なるご迷惑をおかけし、心よりお詫び申し上げます。今後とも変わらぬご愛顧を賜りますようお願い申し上げます。

### Response B

> Plus月額料金改定のお知らせ
>
> 2026年10月1日以降の更新分から、月額料金を1,200円から1,500円に改定します。次回更新日は「アカウント設定」で確認できます。継続しない場合は、次回更新日の前に解約してください。解約後も、現在の支払期間が終了するまでは利用できます。継続する場合、手続きは不要です。

---

## Evaluation Rubric

| Criterion | Weight | Evaluation Standard |
|---|---:|---|
| Semantic accuracy | 25 | Preserves the source meaning, dates, prices, and conditions |
| Instruction following | 15 | Follows the requested format and avoids prohibited additions |
| Naturalness and fluency | 20 | Reads as clear, idiomatic Japanese rather than a literal translation |
| Register and cultural fit | 15 | Uses appropriate politeness without sounding excessive or impersonal |
| Transparency and user trust | 15 | Presents the price change and user choices without obscuring material information |
| Clarity and actionability | 10 | Makes the next action and relevant deadline easy to understand |
| **Total** | **100** | |

---

## Score Summary

| Criterion | Response A | Response B |
|---|---:|---:|
| Semantic accuracy | 15/25 | 25/25 |
| Instruction following | 8/15 | 15/15 |
| Naturalness and fluency | 17/20 | 19/20 |
| Register and cultural fit | 10/15 | 14/15 |
| Transparency and user trust | 5/15 | 15/15 |
| Clarity and actionability | 6/10 | 10/10 |
| **Total** | **61/100** | **98/100** |
| **Decision** | **Major revision required** | **Pass — strongly preferred** |

---

## Issue-Level Analysis

| Response | Text or Behavior | Evaluation | Severity |
|---|---|---|---|
| A | 「サービス品質向上のため」 | Adds a reason that does not appear in the source. This is an unsupported claim, even though it sounds plausible. | Major |
| A | 「2026年10月1日より」 | Omits that the new price applies specifically to renewals on or after the date, making the timing less precise. | Major |
| A | 「アカウント設定から解約できます」 | Does not state that cancellation must occur before the next renewal. | Major |
| A | Cancellation wording | Omits continued access until the end of the current paid period. | Major |
| A | Overall notice | Omits where to find the next renewal date and that no action is needed to continue. | Major |
| A | Strong apology and closing request | Uses polished Japanese, but the excessive apology and request for continued patronage shift attention away from the user's decision. They also violate the instructions. | Minor |
| B | Date, price, and renewal timing | Preserves all material source facts without adding a justification. | Pass |
| B | Cancellation information | States both the deadline and continued access after cancellation. | Pass |
| B | 「継続する場合、手続きは不要です」 | Clearly communicates the no-action option. | Pass |
| B | Overall tone | Uses respectful, direct Japanese appropriate for a transactional notice. | Pass |

---

## Detailed Evaluation

### Response A

Response A initially appears professional because it is fluent and uses familiar customer-service language. However, surface fluency hides several material problems.

The response invents a business justification, even though the source does not explain why the price is changing. It also removes important conditions concerning renewal timing, the cancellation deadline, continued access, and the no-action option. These omissions make it harder for the user to understand the financial consequence and make an informed choice.

The tone is also more apologetic and ceremonial than the instructions permit. Formal phrases such as 「平素よりご愛顧いただき」 are not incorrect by themselves, but they do not compensate for missing decision-critical information.

Because the missing and added content changes the practical meaning of the notice, Response A requires major revision.

### Response B

Response B preserves every material fact from the source:

- The effective date
- The current and new prices
- The fact that the change applies to renewals on or after that date
- Where to find the next renewal date
- The cancellation deadline
- Continued access through the current paid period
- The no-action option

The Japanese is concise, natural, and appropriately respectful. It prioritizes information the user needs to act, rather than adding unsupported corporate messaging.

A minor stylistic alternative would be to use 「ご利用いただけます」 instead of 「利用できます」 for slightly more formal customer-facing language. This does not affect the meaning or rating.

---

## Trust and Safety Analysis

This example is not physically safety-critical, but it still has a meaningful trust dimension.

- An invented explanation can make a business decision appear more justified than the evidence allows.
- Missing cancellation terms can interfere with informed user choice.
- Fluent, polite language can make unsupported or incomplete content harder to notice.

For AI quality work, factual fidelity and user agency must take priority over language that merely sounds polished.

---

## Evaluator Decision

**Response B is strongly preferred.**

Response A is fluent but materially incomplete and contains an unsupported reason for the price change. Response B accurately preserves the source, follows the localization instructions, and gives Japanese users the information needed to decide and act.

The decisive difference is not politeness. It is whether the localization protects the source meaning and the user's ability to make an informed choice.

---

## Improved Final Answer

> **Plus月額料金改定のお知らせ**
>
> 2026年10月1日以降の更新分から、Plusの月額料金を1,200円から1,500円に改定します。次回更新日は「アカウント設定」で確認できます。継続を希望しない場合は、次回更新日の前に解約してください。解約後も、現在の支払期間が終了するまではご利用いただけます。継続する場合は手続き不要です。

---

## Skills Demonstrated

- Japanese localization quality evaluation
- Semantic fidelity and omission detection
- Unsupported-claim identification
- Pairwise response ranking
- Rubric-based scoring
- Cultural and register analysis
- User-trust and transparency assessment
- Structured evaluator rationale writing
