# ClearJP — Case #003
## AI customer support: fluent Japanese that overstates the source

**Japanese AI & Localization Quality Review**

**Website:** [clearjp.com](https://clearjp.com)

Japanese can sound natural and professional while still communicating more than the source actually says.

In AI customer support, that can matter when localized wording changes a suggestion into a completed action, a response-time estimate into a guarantee, or a limited security statement into an absolute promise.

This fictional review examines Japanese support copy against an explicit English source.

**Fictional demonstration, not a client project.**  
The English source lines, Japanese examples, product context, and review findings are synthetic and were created for portfolio purposes. ChatGPT assisted with drafting the exercise and intentionally imperfect examples. No real company, product, customer interaction, support policy, or measured usability result is represented.

## Review brief

- **Audience:** Japanese users of a fictional SaaS product.
- **Content:** AI-assisted customer support messages and UI copy.
- **Source:** Fictional English source text supplied for every reviewed item.
- **Review focus:** Meaning preservation, naturalness, clarity, terminology, action status, certainty, and product claims.
- **Format:** English source → Japanese copy → Review note → Suggested revision → Why it matters.

For this exercise, the **English source is authoritative**. Product behavior not stated in the source or context is treated as unknown.

We use:

- **Improve** — wording should be revised.
- **Keep** — current Japanese is suitable.
- **High** — wording materially changes an action, commitment, capability, or security claim.
- **Medium** — wording affects clarity, recovery, or naturalness.
- **Low** — mainly editorial or terminology consistency.

---

## Review findings

### 01 — Do not turn guidance into a completed action

**Context:** AI response to a user asking how to request a refund.  
**Assessment:** Improve / semantic fidelity, action-status risk — **High**

**English source**

> I'll show you the refund request page.

**Current Japanese**

> 返金処理が完了しました。

**Review note**

The Japanese says that the refund itself has already been processed.

The English source says only that the user will be shown the page where a refund can be requested.

These are different actions and different stages of the workflow.

**Suggested revision**

> 返金の申請ページをご案内します。

**Why it matters**

A user could reasonably believe the refund has already been submitted or completed.

The revision preserves the actual action described by the source without adding an unsupported result.

---

### 02 — Do not turn a contact option into a transfer confirmation

**Context:** Support response containing a link to the support team.  
**Assessment:** Improve / semantic fidelity, workflow risk — **High**

**English source**

> You can contact our support team here.

**Current Japanese**

> 担当チームに転送しました。

**Review note**

The Japanese says the conversation or case has already been transferred.

The English source only gives the user an option to contact support.

**Suggested revision**

> こちらからサポートチームにお問い合わせいただけます。

**Why it matters**

Users should know whether escalation has actually happened or whether they still need to take action.

Natural Japanese is not sufficient if it changes the workflow.

---

### 03 — Do not turn an estimate into a guarantee

**Context:** Message explaining expected support response time.  
**Assessment:** Improve / semantic fidelity, commitment risk — **High**

**English source**

> We usually respond within 24 hours.

**Current Japanese**

> 24時間以内に必ず解決します。

**Review note**

Two meanings have changed.

First, **respond** has become **resolve**.

Second, **usually** has become the absolute **必ず**.

The Japanese therefore promises both a stronger outcome and a stronger timeframe than the source.

**Suggested revision**

> 通常、24時間以内に回答します。

**Why it matters**

Customer-support wording can create operational expectations.

A localization should not strengthen a service commitment beyond the source.

---

### 04 — Do not replace a limited security statement with an absolute claim

**Context:** Account-security information shown in help content.  
**Assessment:** Improve / semantic fidelity, security-claim risk — **High**

**English source**

> We use security measures designed to reduce the risk of unauthorized access.

**Current Japanese**

> お客様のアカウントは100％安全です。

**Review note**

The source describes security measures intended to reduce risk.

The Japanese instead guarantees complete safety.

The absolute claim is not supported by the English source.

**Suggested revision**

> 不正アクセスのリスクを減らすためのセキュリティ対策を実施しています。

**Why it matters**

Security wording should preserve the limits of the source.

More reassuring Japanese is not necessarily more accurate Japanese.

---

### 05 — Natural support copy can be shorter

**Context:** Introduction to troubleshooting instructions.  
**Assessment:** Improve / naturalness, tone — **Medium**

**English source**

> Try the steps below.

**Current Japanese**

> あなたの問題を解決するために以下の手順を実行してください。

**Review note**

The meaning is broadly understandable, but the sentence is heavier and more mechanical than necessary.

「あなたの問題」 is also unnecessary in this context.

**Suggested revision**

> 以下の手順をお試しください。

**Why it matters**

Support copy should help users move quickly to the next action.

The shorter wording preserves the source while sounding more natural in Japanese.

---

### 06 — Preserve useful error information from the source

**Context:** The user attempts to change their plan while an invoice remains unpaid.  
**Assessment:** Improve / completeness, recovery guidance — **Medium**

**English source**

> You can't change your plan because you have an unpaid invoice. Please pay it and try again.

**Current Japanese**

> エラーが発生しました。もう一度やり直してください。

**Review note**

The Japanese removes the specific reason supplied by the source.

It also tells the user to retry without explaining that retrying alone will not solve the problem.

**Suggested revision**

> 未払いの請求があるため、プランを変更できません。お支払い後、もう一度お試しください。

**Why it matters**

When the source already explains the cause and recovery step, localization should preserve that useful information rather than reduce it to a generic error.

---

### 07 — Use one term consistently for the same concept

**Context:** Three labels referring to the same subscription plan.  
**Assessment:** Improve / terminology consistency — **Low**

**English source**

> Change plan  
> Current plan  
> Plan details

**Current Japanese**

> 契約プランを変更  
> 現在のサブスク  
> メンバーシップ詳細

**Review note**

「契約プラン」「サブスク」「メンバーシップ」 can each appear in Japanese products, but using three different terms for the same concept creates unnecessary variation.

The source uses **plan** consistently.

**Suggested revision**

> プランを変更  
> 現在のプラン  
> プランの詳細

**Why it matters**

Terminology consistency helps users recognize that different screens refer to the same object.

The issue is consistency, not that 「サブスク」 or 「メンバーシップ」 is always incorrect.

---

### 08 — Keep wording that already works

**Context:** Password-recovery action.  
**Assessment:** **Keep** / clarity, source fidelity

**English source**

> Reset password

**Current Japanese**

> パスワードを再設定

**Review note**

The Japanese is concise, familiar, and accurately reflects the source.

**Suggested revision**

> パスワードを再設定（変更なし）

**Why it matters**

Quality review is not about rewriting every string.

Good localization should also identify wording that already works and leave it alone.

---

## Revised support copy

| Context | English source | Recommended Japanese |
|---|---|---|
| Refund guidance | I'll show you the refund request page. | 返金の申請ページをご案内します。 |
| Contact support | You can contact our support team here. | こちらからサポートチームにお問い合わせいただけます。 |
| Response time | We usually respond within 24 hours. | 通常、24時間以内に回答します。 |
| Security statement | We use security measures designed to reduce the risk of unauthorized access. | 不正アクセスのリスクを減らすためのセキュリティ対策を実施しています。 |
| Troubleshooting intro | Try the steps below. | 以下の手順をお試しください。 |
| Plan-change error | You can't change your plan because you have an unpaid invoice. Please pay it and try again. | 未払いの請求があるため、プランを変更できません。お支払い後、もう一度お試しください。 |
| Plan terminology | Change plan / Current plan / Plan details | プランを変更 / 現在のプラン / プランの詳細 |
| Password action | Reset password | パスワードを再設定 |

## Review outcome

**Eight reviewed items:** seven Improve, one Keep.

Four High-priority findings changed the meaning of the source in ways that could affect user expectations:

- a refund page became a completed refund,
- a contact option became a completed transfer,
- a typical response time became a guaranteed resolution time,
- and a risk-reduction statement became a 100% security guarantee.

The remaining findings address naturalness, actionable error information, and terminology consistency.

## What this case demonstrates

This exercise demonstrates that Japanese localization quality is not only about whether a sentence sounds fluent.

A reviewer may also need to ask:

- Did the action actually happen?
- Did the Japanese strengthen the source?
- Did uncertainty become certainty?
- Did an estimate become a guarantee?
- Was useful information removed?
- Are the same concepts named consistently?

A sentence can be grammatically correct and natural while still being the wrong localization.

## Review method

1. Read the English source before evaluating the Japanese.
2. Identify the intended action, status, certainty, and commitment in the source.
3. Compare those elements with the Japanese wording.
4. Separate semantic problems from stylistic or terminology issues.
5. Preserve useful source information instead of adding or removing facts.
6. Avoid strengthening claims simply to make the Japanese sound reassuring.
7. Keep suitable wording when revision is unnecessary.
8. Review the final strings together for terminology and workflow consistency.

## Evidence demonstrated

- English-to-Japanese semantic fidelity review
- Japanese SaaS and customer-support copy evaluation
- Action-status and workflow accuracy
- Detection of unsupported certainty and strengthened claims
- Security-claim wording review
- Actionable error-message review
- Terminology consistency
- Selective Keep / Improve judgment

## Scope and limitations

This is an AI-assisted fictional portfolio exercise prepared for Rie Nakahara / ClearJP.

It demonstrates a review method and native-Japanese editorial judgment. It does not represent a real client engagement, product test, legal review, security audit, customer-support SLA assessment, or measured usability improvement.

The English source lines are fictional and authoritative only within this exercise.

**ClearJP — Japanese that preserves what the product actually means.**