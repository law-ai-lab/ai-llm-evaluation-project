# ClearJP — Case #005
## AI onboarding & consent: when optional choices look mandatory

**Japanese AI & Localization Quality Review**

**Website:** [clearjp.com](https://clearjp.com)

A short onboarding sentence can change whether users understand a choice as optional, required, reversible, or bundled with something else.

This fictional case reviews Japanese onboarding and permission copy for an AI assistant. The focus is not legal compliance. It is whether the Japanese accurately communicates the product behavior described in the supplied brief.

**Fictional demonstration, not a client project.**
All product assumptions, Japanese examples, and findings below are synthetic. ChatGPT assisted with drafting this exercise and intentionally imperfect examples for Rie Nakahara / ClearJP. No real company, user study, legal opinion, privacy audit, or measured conversion result is represented.

## Review brief

- **Audience:** Japanese users setting up a fictional AI assistant.
- **Content:** onboarding screens, optional model-improvement permission, analytics information, marketing permission, and settings copy.
- **Available evidence:** the fictional product brief below, authoritative only within this exercise.
- **Review focus:** optionality, data-use boundaries, reversibility, bundled choices, claim support, and natural Japanese.
- **Format:** Context → source/product fact → Japanese copy → review note → suggested revision → why it matters.

### Fictional product facts

| ID | Product fact | Boundary for this exercise |
|---|---|---|
| B1 | Users can use the core service without allowing their content to be used for model improvement. | Model-improvement participation is optional. |
| B2 | The model-improvement option is off by default. | Users must actively choose it. |
| B3 | Users can change this setting later. | The setting can be changed; effects on prior content use are unspecified. |
| B4 | Product analytics and model-improvement use are separate processes. | One should not be described as the other. |
| B5 | No information is supplied about anonymization, de-identification, or human review of content. | Do not invent those assurances. |
| B6 | Uploaded content is processed in the cloud, but the retention period is unspecified. | Do not invent a deletion schedule. |
| B7 | Marketing emails require a separate optional choice. | Marketing permission should not be bundled with model-improvement participation. |
| B8 | The primary button continues setup whether or not the optional model-improvement box is selected. | Continuing setup should not imply consent. |

These are fictional exercise assumptions, not facts about a real product.

We use:

- **Improve** — wording can be corrected from the supplied product facts.
- **Resolve** — the claim requires product-owner evidence before publication.
- **Keep** — wording is suitable and supported.
- **High** — wording could materially alter the user's understanding of choice, data use, or required action.
- **Medium** — wording affects clarity or recovery.
- **Low** — mainly editorial consistency.

## Review findings

### 01 — Do not make optional participation look required

**Context:** Onboarding text above the model-improvement checkbox.  
**Assessment:** Improve / optionality, clarity — **High**

**Source / product fact:** B1 says the core service works without this permission.

**Japanese copy**

> AI機能をご利用いただくには、データ利用への同意が必要です。

**Review note**

The sentence makes the data-use choice sound mandatory for using the AI service.

That contradicts the fictional product brief. B2 also specifies that the option is off by default. The actual checkbox state must match that behavior; a wording change cannot correct a preselected control.

**Suggested revision**

> コンテンツのモデル改善への利用は任意です。許可しなくても、基本機能をご利用いただけます。

**Why it matters**

Users should be able to distinguish access to the service from an optional data-use choice.

---

### 02 — The primary button should not imply consent

**Context:** Main button beneath the optional checkbox.  
**Assessment:** Improve / choice and action clarity — **High**

**Source / product fact:** B8 says setup continues whether or not the checkbox is selected.

**Japanese copy**

> 同意して開始

**Review note**

The button implies that continuing setup itself means agreeing to the optional setting.

**Suggested revision**

> 設定を続ける

**Why it matters**

The primary action should describe what happens for every user, not only for users who select an optional permission.

---

### 03 — Keep analytics and model improvement separate

**Context:** Explanation below the optional setting.  
**Assessment:** Improve / data-use boundary — **High**

**Source / product fact:** B4 says analytics and model-improvement use are separate processes.

**Japanese copy**

> 利用状況データは、AIの学習とサービス分析のために使用されます。

**Review note**

The Japanese combines two different processes into one statement.

A user could reasonably understand this as meaning all analytics data is also used for model improvement. The brief does not establish the analytics data categories, controls, or notice destination; those details remain questions for the product owner.

**Suggested revision**

> モデル改善への利用は、この設定で選択します。利用状況の分析とモデル改善への利用は、別の処理です。

**Why it matters**

Separate processes should remain separate in the interface so users can understand what each choice controls.

---

### 04 — Do not invent anonymization

**Context:** Reassurance beside the optional model-improvement setting.  
**Assessment:** Resolve / unsupported privacy assurance — **High**

**Source / product fact:** B5 supplies no anonymization or de-identification claim.

**Japanese copy**

> データは匿名化されるため、個人が特定されることはありません。

**Review note**

This introduces both an anonymization process and an absolute outcome that the brief does not establish.

Missing evidence does not prove the opposite. It means the reviewer cannot approve the claim yet.

**Suggested revision**

> **Hold this reassurance. No publishable replacement claim is approved until the actual data-handling process is confirmed.**

**Why it matters**

The explanation needs an evidenced description of data handling. A language revision cannot supply an undocumented process.

---

### 05 — Do not promise that no human will ever see content

**Context:** FAQ during onboarding.  
**Assessment:** Resolve / unsupported review-process claim — **High**

**Source / product fact:** B5 does not establish whether human review or support access can occur.

**Japanese copy**

> アップロードした内容を人が確認することは一切ありません。

**Review note**

The absolute statement is unsupported.

The brief does not establish that human review occurs, but neither does it support saying that it never occurs.

**Suggested revision**

> **Hold this statement.** Confirm whether employees, contractors, support staff, safety reviewers, or other authorized personnel can access content under any circumstances.

**Why it matters**

Users may rely heavily on absolute privacy statements when deciding what information to upload.

---

### 06 — Do not invent a deletion schedule

**Context:** Storage explanation below the upload control.  
**Assessment:** Resolve / retention claim — **High**

**Source / product fact:** B6 confirms cloud processing but supplies no retention period.

**Japanese copy**

> アップロードしたデータは処理後すぐに削除されます。

**Review note**

The deletion timing is not supported by the brief.

**Suggested revision**

> アップロードしたデータはクラウド上で処理されます。

This sentence states only the known processing location; it does not answer the retention question. Keep the retention claim on hold and add a retention statement only after the actual period and conditions are confirmed.

**Why it matters**

A concrete deletion promise should come from documented product behavior rather than a localization assumption.

---

### 07 — Keep marketing permission separate

**Context:** Checkbox at the end of onboarding.  
**Assessment:** Improve / bundled choice — **High**

**Source / product fact:** B7 says marketing emails are a separate optional choice.

**Japanese copy**

> サービス改善への協力および最新情報の受信に同意します。

**Review note**

This bundles two unrelated choices into one checkbox.

**Suggested revision**

Model improvement:

> コンテンツをモデル改善に利用することを許可する（任意）

Marketing:

> マーケティングメールを受け取る（任意）

**Why it matters**

Different choices should be visible as different choices.

Bundling them makes the user's actual intent harder to understand. These revisions require two separate controls and appropriately separate records, not just two lines of text within one checkbox. Confirm the implementation before release.

---

### 08 — Keep a clear reversibility message

**Context:** Helper text below the optional setting.  
**Assessment:** **Keep** / clarity, source fidelity

**Source / product fact:** B3 says the setting can be changed later.

**Japanese copy**

> この設定は後から変更できます。

**Review note**

The sentence is concise, natural, and accurately communicates that the setting can be changed later. It does not establish deletion of prior uploads, reversal of earlier model-improvement use, or the timing of a setting change. Do not extend it into those assurances without evidence.

**Suggested revision**

> この設定は後から変更できます。

Unchanged.

**Why it matters**

Quality review should preserve wording that already communicates the product behavior clearly.

## Revised copy summary

| Item | Decision | Suggested wording / disposition |
|---|---|---|
| Optional participation | Improve / High | コンテンツのモデル改善への利用は任意です。許可しなくても、基本機能をご利用いただけます。 |
| Primary button | Improve / High | 設定を続ける |
| Analytics vs model improvement | Improve / High | モデル改善への利用は、この設定で選択します。利用状況の分析とモデル改善への利用は、別の処理です。 |
| Anonymization | Resolve / High | Hold pending confirmed data-handling evidence. |
| Human review | Resolve / High | Hold pending confirmed access/review process. |
| Retention | Resolve / High | Known processing only: アップロードしたデータはクラウド上で処理されます。 Retention wording remains on hold. |
| Marketing permission | Improve / High | Separate model-improvement and marketing choices. |
| Reversibility | Keep | この設定は後から変更できます。 |

## Questions for a real product owner

1. Is model-improvement participation optional for every user and plan?
2. What exact data is covered by the model-improvement setting?
3. Are analytics and model-improvement pipelines separate?
4. Is any anonymization or de-identification performed, and what can accurately be claimed about it?
5. Can employees, contractors, support staff, or safety reviewers access user content under any conditions?
6. What is the retention period for uploaded content and related data?
7. Is marketing permission stored separately from product-data choices?
8. Where can users later change each setting, when do changes take effect, and what happens to content previously used?

These are confirmation questions, not facts about a real product.

## Review outcome

**Eight findings: four Improve, three Resolve, one Keep.**

Seven identified issues are High priority because they affect the user's understanding of optionality, data use, or assurance.

The review corrects wording that makes optional participation look required, separates unrelated permissions, and holds privacy claims that lack evidence. It also preserves a clear setting-change message. The three Resolve findings remain open; the known cloud-processing sentence does not resolve retention.

## What this case demonstrates

Good Japanese onboarding copy is not only natural language.

It must also preserve the structure of the user's choice.

A polished sentence can still be misleading if it:

- turns an optional setting into a requirement,
- makes continuing look like consent,
- bundles unrelated permissions,
- or adds privacy assurances that the product brief does not support.

The review task is therefore partly linguistic and partly evidentiary:

**What exactly does the product do, and what can the interface truthfully say about it?**

## Review method

1. Establish product behavior before editing the Japanese.
2. Identify every choice, default, and downstream action.
3. Separate required actions from optional permissions.
4. Map each privacy or data-use statement to explicit evidence.
5. Use Improve, Resolve, or Keep rather than rewriting everything.
6. Avoid replacing an unsupported absolute claim with a softer unsupported claim.
7. Review the final screen as one flow so buttons, helper text, and checkboxes do not contradict each other.

### Evidence demonstrated

- Japanese AI onboarding and permission-copy evaluation
- Optionality and action-status review
- Separation of analytics, model-improvement, and marketing choices
- Detection of unsupported privacy and retention assurances
- Product-owner escalation for missing evidence
- Context-sensitive Japanese revision
- Selective Keep judgment

## Scope and limitations

This is an AI-assisted fictional portfolio exercise prepared for Rie Nakahara / ClearJP.

It demonstrates a review method and native-Japanese editorial judgment. It is not legal advice, a privacy assessment, a compliance audit, a real client engagement, or measured usability research.

The supplied product facts are fictional and authoritative only within this exercise. In real work, relevant product, implementation, privacy, and legal owners must confirm the behavior and evidence behind publishable claims.

**ClearJP — Japanese that makes the user's choice clear.**

**Numbering:** ClearJP Case #005 belongs to the ClearJP series.
