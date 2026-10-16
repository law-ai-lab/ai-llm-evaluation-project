# ClearJP — Case #004
## AI product claims: when persuasive Japanese invents product facts

**Japanese AI & Localization Quality Review**

**Website:** [clearjp.com](https://clearjp.com)

An AI-generated product page can introduce a feature that nobody specified. A polished Japanese sentence may hide that addition because it reads like ordinary marketing copy.

This case reviews a fictional tool for drafting online-store product descriptions. The task is to trace each publishable claim to a supplied product brief, distinguish contradictions from missing evidence, and separate language edits from decisions requiring a product owner.

**Fictional demonstration, not a client project.** All product assumptions, Japanese examples, claim numbers, and findings below are synthetic. ChatGPT assisted with drafting the exercise, intentionally flawed examples, and analysis for Rie Nakahara / ClearJP. No real company, customer, benchmark, specialist review, or independently validated product capability is represented. The exercise does not establish that a particular model generated these errors in a real test.

## Review brief / product assumptions

- **Audience:** Japanese online-store operators preparing product listings.
- **Content:** AI-assisted Japanese landing-page copy, feature descriptions, badges, and a writing-style control.
- **Available evidence:** The fictional English product brief below, authoritative only within this exercise.
- **Review focus:** Invented capabilities, accuracy and performance claims, automation boundaries, completeness, human-review claims, and contextual clarity.
- **Format:** Context → source/product fact → Japanese copy → review note → suggested revision → why it matters.

### Evidence register

| ID | Supplied English product fact | Boundary for this exercise |
|---|---|---|
| B1 | Users enter product information as text or upload a CSV. Image input and image analysis are not available. | No capability to determine material, size, or other properties from a product photo. |
| B2 | The tool drafts descriptions from supplied fields. Missing material and care information must remain unspecified. | It does not independently establish product attributes or guarantee completeness. |
| B3 | No factual-accuracy evaluation results are supplied. Users are responsible for checking descriptions before use. | An accuracy percentage needs evidence that is absent here. |
| B4 | Users manually export a CSV. The tool has no store connection or automatic publishing function. | Export is available; updating a live store is not. |
| B5 | No time-saving study or comparative performance benchmark is supplied. | No numerical productivity claim is established. |
| B6 | A mock-up includes a proposed badge reading "Reviewed." Its reviewer, criteria, and workflow are undocumented. | Whether any human or specialist review occurs is unknown. |
| B7 | Users can choose a writing style. That style applies to descriptions in the selected batch. | A writing-style control, not an audio or voice feature. |
| B8 | The tool creates proposed product descriptions from the product information a user supplies. | This limited functional description is supported by the brief. |

The brief is the exercise evidence, not proof of a real implementation. A missing fact is not permission to fill it with a plausible product promise. Equally, missing evidence does not prove a claim false.

### Decisions and priority

- **Improve:** A bounded revision can be derived from the supplied brief.
- **Resolve:** A factual claim or review process needs owner/evidence confirmation before publication. The claim remains on hold even if nearby copy can be improved.
- **Keep:** The wording is suitable and supported within the exercise.
- **High:** A claim could materially change a buyer's understanding of capabilities, reliability, required work, or assurance.
- **Medium:** The wording obscures a function or creates avoidable ambiguity.
- **Low:** Mainly editorial polish; not needed for the findings below.

These are qualitative review judgments, not measured impacts or release approvals.

## Review findings

### 01 — A product photo is not an available input

**Context:** Feature card describing how merchants start a listing.  
**Assessment:** Improve / invented capability — **High**

**Source / product fact:** B1 allows text and CSV input and explicitly excludes image analysis.

**Japanese copy**

> 商品写真をアップロードするだけで、AIが素材やサイズを読み取り、商品説明を作成します。

**Review note**

The sentence invents both an image-input route and the ability to infer physical product attributes. This contradicts B1. Even a future image-input feature would not by itself establish reliable material or size recognition.

**Suggested revision**

> 商品情報をテキストで入力するか、CSVで取り込むと、入力内容をもとに商品説明文の案を作成します。

**Why it matters**

A merchant could select the tool for an unavailable workflow. Replacing 「読み取り」 with a softer synonym would leave the invented feature intact; the input and capability need correction.

### 02 — An accuracy percentage needs a defined evaluation

**Context:** Landing-page proof point beside the feature description.  
**Assessment:** Resolve / unsupported accuracy claim — **High**

**Source / product fact:** B3 supplies no factual-accuracy evaluation.

**Japanese copy**

> 商品情報の正確性99.8％。

**Review note**

The percentage has no supporting result in the brief. "Accuracy" also has no defined unit: correct individual attributes, complete descriptions, or something else. The reviewer cannot establish a lower number or infer that the tool is inaccurate.

**Suggested revision**

**Hold the percentage; no replacement numerical claim is approved.** Remove this proof point from the release candidate pending an evaluation definition and supporting results. A separate functional sentence based on B8 may be used without presenting it as evidence of accuracy.

**Why it matters**

A precise number can look like validation. Its apparent precision does not supply a test population, scoring method, or result.

### 03 — CSV export does not connect a store

**Context:** Feature paragraph explaining deployment to an online store.  
**Assessment:** Improve / false automation claim — **High**

**Source / product fact:** B4 provides manual CSV export and explicitly excludes store connections and automatic publishing.

**Japanese copy**

> お使いのストアと連携し、商品ページを自動で更新します。

**Review note**

This invents an integration and a live-store update function. The available export function does not establish compatibility with every destination's import format, either.

**Suggested revision**

> 作成した説明文は、CSVで手動エクスポートできます。

**Why it matters**

Buyers need to know which part of the publishing workflow remains theirs. Do not add a one-click import or supported-store list without product evidence.

### 04 — A productivity number cannot be generated into evidence

**Context:** Hero-page benefit claim.  
**Assessment:** Resolve / fabricated performance figure — **High**

**Source / product fact:** B5 supplies no time-saving study or comparative benchmark.

**Japanese copy**

> 商品登録にかかる作業時間を80％削減。

**Review note**

The figure is intentionally fabricated for this exercise. No baseline, measured task, sample, or result supports it. "Product registration" also covers more work than drafting descriptions; the brief does not establish a benefit across that whole process.

**Suggested revision**

**Hold the quantified benefit.** Do not substitute 「大幅に削減」 or a smaller percentage without evidence. For this page location, use a supported feature description instead:

> 入力した商品情報から、商品説明文の案をまとめて作成できます。

Batch scope follows B7. This replacement describes a function; it is not an approved time-saving claim.

**Why it matters**

The revision removes the invented measurement rather than disguising it as an unmeasured comparative promise.

### 05 — Completing prose is not completing the product record

**Context:** Benefit card for merchants with incomplete source fields.  
**Assessment:** Improve / unsupported completeness and attribute claims — **High**

**Source / product fact:** B2 says missing material and care information must remain unspecified.

**Japanese copy**

> 不足している素材やお手入れ情報もAIが補い、必要な商品情報を100％網羅します。

**Review note**

The first clause contradicts the stated handling of missing facts. The second promises completeness without a defined set of required fields. Generating a plausible care instruction is not evidence that the instruction applies to the item.

**Suggested revision**

> 素材やお手入れ方法など、説明文に含めたい商品情報を入力してください。不明な情報は追加しません。

The final sentence describes B2's declared behavior. It would require implementation confirmation before use for a real product.

**Why it matters**

A finished-looking listing can conceal missing information. Preserve those gaps for owner confirmation instead of converting them into product facts.

### 06 — A badge cannot establish a human-review process

**Context:** Japanese expansion of the proposed "Reviewed" badge.  
**Assessment:** Resolve / unconfirmed human-review assurance — **High**

**Source / product fact:** B6 leaves reviewer identity, criteria, and workflow undocumented.

**Japanese copy**

> 専門スタッフによる確認済み

**Review note**

The Japanese adds a specialist and an implied completed human check. Neither is established by the mock-up. It would also be unsupported to assert that no human review occurs or to replace this with 「AIによる検証済み」.

**Suggested revision**

**Hold the badge; no publishable assurance wording yet.** Ask who reviews what, at which stage, under which criteria, and whether the status applies to every description or a specific checked item.

**Why it matters**

A short badge can imply a substantial quality-control process. That process needs confirmation before a language reviewer can name it accurately.

### 07 — In a text editor, "voice" needs a text-specific label

**Context:** Helper text below the writing-style selector.  
**Assessment:** Improve / naturalness and contextual clarity — **Medium**

**Source / product fact:** B7 applies the selected writing style to descriptions in a batch; there is no audio feature in this control.

**Japanese copy**

> 商品説明を一貫した声で生成します。

**Review note**

「一貫した声」 is a literal rendering of a writing metaphor and can suggest audio in this interface. Here, 「文体」 identifies the setting the user has just selected. The issue is context, not a rule that 「声」 is always unsuitable in brand writing.

**Suggested revision**

> 選択した文体で、今回の説明文をまとめて作成します。

**Why it matters**

The helper explains the setting's scope without implying consistency across every past or future listing.

### 08 — A supported functional description can stay

**Context:** Introductory sentence explaining the tool's purpose.  
**Assessment:** **Keep** / claim support and clarity

**Source / product fact:** B8 establishes creation of proposed descriptions from user-supplied product information.

**Japanese copy**

> 入力した商品情報をもとに、説明文の案を作成します。

**Review note**

The sentence names the input and the deliverable without adding an input method, measurement, assurance, or publishing feature.

**Suggested revision**

> 入力した商品情報をもとに、説明文の案を作成します。

Unchanged. This sentence is supported within the exercise; it does not validate the contents of any generated description.

**Why it matters**

Keeping a useful description provides a practical alternative to filling every marketing slot with a stronger claim.

## Revised copy summary

These are exercise recommendations. A held claim is not approved simply because another sentence is usable.

| Item | Decision | Evidence state | Suggested wording / disposition |
|---|---|---|---|
| 01 — Photo analysis | Improve / High | Contradicts B1 | 商品情報をテキストで入力するか、CSVで取り込むと、入力内容をもとに商品説明文の案を作成します。 |
| 02 — 99.8% accuracy | Resolve / High | Unsupported by B3 | Hold the percentage; obtain evaluation evidence. |
| 03 — Store updates | Improve / High | Contradicts B4 | 作成した説明文は、CSVで手動エクスポートできます。 |
| 04 — 80% time saving | Resolve / High | Unsupported by B5 | Hold the benefit claim. Functional alternative: 入力した商品情報から、商品説明文の案をまとめて作成できます。 |
| 05 — Complete missing facts | Improve / High | Contradicts B2; completeness undefined | 素材やお手入れ方法など、説明文に含めたい商品情報を入力してください。不明な情報は追加しません。 |
| 06 — Specialist reviewed | Resolve / High | Process unknown under B6 | Hold the badge pending process confirmation. |
| 07 — Writing-style helper | Improve / Medium | Function supported by B7 | 選択した文体で、今回の説明文をまとめて作成します。 |
| 08 — Functional introduction | Keep | Supported by B8 | 入力した商品情報をもとに、説明文の案を作成します。 |

## Questions for a real product owner

1. Which released version, input types, and product fields does this page describe? Can implementation demonstrate each stated feature?
2. How are missing attributes handled in generated text? Can unsupported materials, dimensions, or care instructions be inserted despite the intended behavior?
3. For any accuracy claim, what is the measured unit, dataset, language, scoring procedure, sample size, model/version, and result? Who owns the evidence and its applicable scope?
4. For any time-saving claim, what task and baseline were compared? Were input preparation, corrections, checking, and store publication included?
5. Does export include any confirmed destination formats or integrations? Which steps remain manual?
6. What does "Reviewed" mean in the shipped workflow? Is the reviewer human, a specialist, an automated check, or some combination? What does that check actually cover?
7. Does the writing-style setting apply only to the current batch, and are any exceptions known?
8. Who must approve the final product claims, and how will evidence be rechecked after product changes?

These are confirmation questions, not facts about a real service.

## Review outcome

**Eight findings: four Improve, three Resolve, one Keep.** Six are High priority; one is Medium; the Keep item has no issue priority.

The review removes two invented workflow capabilities, exposes unsupported accuracy and productivity numbers, preserves missing product facts as missing, and holds an undocumented review badge. It also clarifies one writing-style message and retains a supported functional sentence.

The three Resolve findings stay open until their evidence questions are answered. No evaluation, human-review process, or release sign-off was performed by this exercise.

## What this case demonstrates

The useful output of claim review is a traceable decision: supported, contradicted, or unresolved, followed by an appropriate editorial action.

An unsupported claim and a known false feature need different treatment. A contradiction can be corrected to match the supplied brief; an unsubstantiated measurement needs evidence or removal. A translation that sounds plausible cannot close either evidence gap.

## Review method

1. Establish the evidence register before editing the Japanese.
2. Extract each distinct claim, including claims hidden inside short badges and numbers.
3. Map the claim to a specific brief item and mark it supported, contradicted, or unresolved.
4. Separate a language issue from a missing product fact or missing evaluation.
5. Use Improve, Resolve, or Keep and assign qualitative priority to identified issues.
6. Make bounded revisions; record held claims and questions for the accountable owner.
7. Check the revised copy together so one sentence does not restore a promise removed elsewhere.

### Evidence demonstrated

- Japanese AI-assisted product-copy evaluation against an explicit brief.
- Claim-to-evidence mapping and differentiation of absence from contradiction.
- Detection of invented input capabilities and integrations.
- Review of numerical accuracy, productivity, and completeness claims.
- Identification of implied specialist/human review without a documented process.
- Context-sensitive language editing and selective Keep judgment.
- A claim disposition table and product-owner confirmation queue.

## Scope and limitations

This AI-assisted fictional portfolio exercise documents a review approach. It does not demonstrate paid client work, independent human validation, actual model error rates, conversion improvement, a benchmark, product testing, or legal compliance.

The supplied brief is deliberately limited and fictional. No real technical capability or performance claim can be inferred from it. In actual work, product owners must confirm implementation and evidence; a qualified reviewer must validate the final Japanese in context.

**Numbering:** ClearJP Case #004 is part of the ClearJP series and is separate from the repository's LLM Evaluation Case 004.
