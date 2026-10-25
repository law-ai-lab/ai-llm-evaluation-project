# ClearJP — Case #007
## AI error messages: when Japanese makes the user feel blamed

**Japanese AI & Localization Quality Review**  
**Website:** [clearjp.com](https://clearjp.com)

Error copy has two jobs: describe the state accurately and help the person decide what to do next. Grammatically natural Japanese can still assign unnecessary blame, hide partial completion or recommend an action that cannot work.

**Good error copy should explain the problem without making the person feel like the problem.** That does not require an apology in every message or softer wording at the expense of useful instructions.

**Fictional demonstration, not a client project.** The unnamed product, Japanese strings, interface states, limits and counts below were created for this portfolio exercise. ChatGPT assisted with the examples, drafting and analysis for Rie Nakahara / ClearJP. They are not sampled outputs from a tested model or observations about a real company. No user study, psychological outcome, conversion improvement or independent validation is represented.

## Review brief / fictional product context

An AI-assisted content workspace lets adult users import reference records, generate summaries and outlines, and prepare editable drafts. The review covers Japanese error and recovery copy, not the underlying model's output quality.

The voice is calm, direct and helpful. A user can correct a field without being described as careless or incompetent. A system can acknowledge a failure without pretending that every cause is known.

### Fictional evidence register

These are declared exercise assumptions, not verified facts about a released product.

| ID | Source / product fact supplied for this exercise | Copy boundary |
|---|---|---|
| E1 | The publication-date field accepts YYYY-MM-DD. A different format is rejected before submission; the date remains editable. | Explain the required format, without claiming that the person's overall method is wrong. |
| E2 | Loading the reference list failed. Records were not changed. The visible “再読み込み” control repeats a read-only request. | A reload is supported; re-uploading, data-loss assurances beyond this operation, and network-cause claims are not. |
| E3 | Outline generation was unavailable because the generation service returned a temporary-unavailability state. No new outline was saved; the existing draft remains unchanged. A fresh generation attempt can be made later. | Attribute the unsuccessful operation to generation, not the user's ability or prompt quality. Do not promise a recovery time. |
| E4 | The session expired before an AI rewrite request was accepted. The editor keeps the current text while the person signs in again. | Say what requires sign-in and what is retained; do not imply account suspension or a security incident. |
| E5 | A fictional batch imported 10 of 12 reference records. Two were rejected because their required titles were empty. Imported records are listed separately from the two editable rejected records. | State partial success. Direct correction to the two rejected records, without asking for the whole batch again. |
| E6 | AI summarization cannot read a selected document because the current account lacks access. The supplied brief does not establish who may grant access or any supported access-request / alternative-document flow. | Repeating the same request cannot remove the permission condition. Complete recovery guidance needs owner confirmation. |
| E7 | AI autofill stopped before completing a content form. Existing field values remain editable. Manual completion and saving an incomplete draft are both supported; publication still requires the required fields. | Offer the actual alternatives. A draft is not a published item, and AI completion is not compulsory. |
| E8 | The prompt counter uses the same character-counting rule as validation. The maximum is 2,000 characters; this fictional entry has 2,148. Validation occurs before generation. Reducing the entry to the limit permits resubmission. | Give the actual limit and actionable reduction. Do not remove the constraint merely to sound warmer. |

The register is the reference for every recommendation. It does not establish that the implementation has been tested.

### Decisions and priorities

- **Improve:** The supplied facts support a bounded revision.
- **Resolve:** A product fact or recovery route is missing; hold the complete message for confirmation. A supported status sentence may still be proposed.
- **Keep:** Existing wording fits the state, relationship and next action.
- **High:** Copy could obscure partial completion or direct the person into an ineffective recovery loop.
- **Medium:** Copy obscures the correction, assigns responsibility poorly, or adds avoidable distance in this context.
- **Low:** A minor editorial preference. No finding here requires that label.

Priorities are qualitative editorial judgments, not measured user harm or release approval.

## Review findings

### 01 — Name the format, not the person's mistake

**Context:** Publication-date validation in the reference-record form.  
**Source / product fact:** E1; the accepted format is known and the field can be edited.  
**Assessment:** **Improve / Medium**

**Current Japanese**

> 入力方法が間違っています。

**Review note**

The sentence is grammatical, but it judges the person's method without identifying the condition that failed. The product knows something narrower: this field needs a particular date format. Replacing 「間違っています」 with a vague apology would still leave the person without that information.

**Suggested revision**

> 日付を「2026-10-25」のように、年-月-日の形式で入力してください。

**Why it matters**

The example makes the required correction available in the message itself. A clear 「ください」 instruction is appropriate when it describes a supported, necessary correction.

### 02 — Turn a vague failure into a supported recovery action

**Context:** The reference list cannot be displayed.  
**Source / product fact:** E2; only a read request failed, records were unchanged, and “再読み込み” is available.  
**Assessment:** **Improve / Medium**

**Current Japanese**

> エラーが発生しました。

**Review note**

The message reports an event but omits the affected operation and available action. It does not establish that the user's internet connection caused the problem. “Check your connection” would add an unsupported diagnosis.

**Suggested revision**

> 一覧を読み込めませんでした。「再読み込み」を選んで、もう一度お試しください。

**Why it matters**

The person can connect the message to the visible control. The recommendation is supported because this control repeats a read-only request; that reasoning must not be generalized to payments or other actions with side effects.

### 03 — Describe unavailable generation without judging the user

**Context:** An outline request returns no new result.  
**Source / product fact:** E3; generation is temporarily unavailable and the existing draft is unchanged.  
**Assessment:** **Improve / Medium**

**Current Japanese**

> アウトライン作成に失敗しました。正しくやり直してください。

**Review note**

「失敗しました」 alone is not inherently accusatory in Japanese: its subject may be a system process. Here, however, 「正しくやり直してください」 suggests that the person performed the action incorrectly. The supplied state provides no basis for evaluating the prompt or the user's competence.

**Suggested revision**

> 現在、アウトラインを作成できません。下書きは変更されていません。時間をおいて、もう一度お試しください。

**Why it matters**

The message separates service availability, draft state and the next action. It does not promise that a retry will succeed or invent a five-minute recovery estimate.

### 04 — Explain an expired session without ceremonial alarm

**Context:** An AI rewrite request is stopped by an expired session.  
**Source / product fact:** E4; the request was not accepted and the current editor text is kept during sign-in.  
**Assessment:** **Improve / Medium**

**Current Japanese**

> 認証情報の失効に伴い、本機能のご利用を継続いただくことができない状態となっております。再認証のお手続きをお願い申し上げます。

**Review note**

The wording is formal and technically styled, but it makes a routine session boundary difficult to interpret. It need not imply a compromised account or suspension. An enthusiastic “Don't worry!” would also be unnecessary and would not explain what happened.

**Suggested revision**

> ログインの有効期限が切れました。入力した文章は保持されています。もう一度ログインしてから、書き換えを実行してください。

**Why it matters**

The message identifies the condition and the supported sequence. The retention statement belongs here only because E4 explicitly supplies it.

### 05 — An apology must not hide partial completion

**Context:** A reference-record batch contains two rejected items.  
**Source / product fact:** E5; 10 records were imported and two with empty titles remain available for correction.  
**Assessment:** **Improve / High**

**Current Japanese**

> ご不便をおかけし、誠に申し訳ございません。処理を完了できませんでした。

**Review note**

The apology gives no operational state. A reader could reasonably be unsure whether anything was imported. “Please try again” would be insufficient because it fails to identify which records need correction. The important revision is state clarity, not merely shortening the honorifics.

**Suggested revision**

> 12件中10件を取り込みました。残り2件はタイトルが未入力です。未取り込みの2件にタイトルを入力して、取り込みを実行してください。

**Why it matters**

The person can distinguish completed work from remaining work. The numbers are fictional state data, not performance measurements, and must be generated from the actual batch state in a real implementation.

### 06 — Do not prescribe a retry that cannot fix permissions

**Context:** AI summarization cannot access a selected reference document.  
**Source / product fact:** E6; access is absent, but the authorized recovery workflow is not supplied.  
**Assessment:** **Resolve / High**

**Current Japanese**

> アクセス権限エラーです。もう一度お試しください。

**Review note**

Repeating the same action leaves the known prerequisite unchanged. The reviewer should not invent an access-request button, nominate a document owner or promise that another file can be selected. Those may be useful product options, but the brief does not establish them.

**Suggested revision**

> この資料を開く権限がないため、要約を作成できませんでした。

**Hold complete recovery guidance pending confirmation.** This is a supported status statement, not approval of a complete error experience. Confirm the access-grant process and any actual alternative path before adding a next step.

**Why it matters**

A courteous but ineffective retry instruction can still keep someone stuck. Dignity includes accurate guidance about what the person can control and what requires someone else's action.

### 07 — Offer the real alternatives when AI assistance stops

**Context:** AI autofill has not completed a form.  
**Source / product fact:** E7; current fields can be edited and an incomplete draft can be saved. Required fields still govern publication.  
**Assessment:** **Improve / Medium**

**Current Japanese**

> 自動入力エラー。自分で入力してください。

**Review note**

The clipped status followed by 「自分で」 sounds like handing the failure back to the person. Manual entry is a real option, but it is not the only one. The alternative must not be described as “continue without required fields,” because the product permits only draft saving in that state.

**Suggested revision**

> 自動入力を完了できませんでした。内容を確認して手入力するか、今回は下書きとして保存できます。

**Why it matters**

The message acknowledges the interrupted assistance and leaves a supported choice with the user. It does not claim that the partially filled content is correct or that saving publishes it.

### 08 — Keep a direct correction when it is specific and useful

**Context:** A prompt exceeds the documented character limit.  
**Source / product fact:** E8; the entry is 2,148 characters against a 2,000-character maximum, with matching counter and validator rules.  
**Assessment:** **Keep**

**Current Japanese**

> 入力は2,000文字までです。148文字以上減らして、もう一度お試しください。

**Review note**

The message names the constraint and gives a correct, actionable reduction. A direct request is appropriate here. Adding a long apology or “you did nothing wrong” would not improve the correction and could distract from it.

**Suggested revision**

> 入力は2,000文字までです。148文字以上減らして、もう一度お試しください。

Unchanged.

**Why it matters**

Not every limit is blame, and not every retry is ineffective. Here the person can change the relevant condition before resubmitting. Keep the number synchronized with actual validation.

## Revised-copy summary

| Item | Decision / priority | Suggested wording / disposition |
|---|---|---|
| 01 — Date format | Improve / Medium | 日付を「2026-10-25」のように、年-月-日の形式で入力してください。 |
| 02 — Failed list load | Improve / Medium | 一覧を読み込めませんでした。「再読み込み」を選んで、もう一度お試しください。 |
| 03 — Unavailable generation | Improve / Medium | 現在、アウトラインを作成できません。下書きは変更されていません。時間をおいて、もう一度お試しください。 |
| 04 — Expired session | Improve / Medium | ログインの有効期限が切れました。入力した文章は保持されています。もう一度ログインしてから、書き換えを実行してください。 |
| 05 — Partial import | Improve / High | 12件中10件を取り込みました。残り2件はタイトルが未入力です。未取り込みの2件にタイトルを入力して、取り込みを実行してください。 |
| 06 — Missing document access | Resolve / High | Supported status only: この資料を開く権限がないため、要約を作成できませんでした。 Confirm the authorized recovery path. |
| 07 — Incomplete autofill | Improve / Medium | 自動入力を完了できませんでした。内容を確認して手入力するか、今回は下書きとして保存できます。 |
| 08 — Known character limit | Keep | 入力は2,000文字までです。148文字以上減らして、もう一度お試しください。 |

## Questions for a real product / content owner

1. Which error states can the interface distinguish reliably, and where is the cause still unknown?
2. Is each recovery instruction matched to an available, correctly named control?
3. Which operations can be repeated safely? What prevents duplicate or conflicting work?
4. How is partial completion represented, and can rejected items be corrected separately?
5. Exactly what text is retained during sign-in, on which devices and for how long?
6. Who may grant document access? Is a request, contact or alternative-document flow actually supported?
7. Which fields are required for publication, and what can be saved as an incomplete draft?
8. Do character counters and server validation share the same counting rule?
9. How will the messages be reviewed in their actual layouts, including keyboard and assistive-technology use?

These questions are a confirmation queue, not claims about a real product.

## Review outcome

**Eight findings: six Improve, one Resolve, one Keep.** Two High-priority and five Medium-priority findings; the Keep example has no remedial priority.

The revisions replace personal judgments, opaque statuses and disproportionate formality with state-specific Japanese. Partial completion is made explicit. One permission-related message remains incomplete until the product owner supplies an authorized path forward.

No improvement in trust, emotion, usability, conversion or recovery success was measured. These are editorial recommendations based on a fictional brief.

## What this case demonstrates

Error quality is a relationship between **known state → responsibility → available action → Japanese wording**. A warmer sentence cannot compensate for a false diagnosis or an impossible instruction.

Human editorial judgment is needed to decide what should be attributed to the system, what the person can change and how direct the language should be. AI can produce considerate language; the review tests whether the proposed language is appropriate and supported here.

**Distinct from Case #006:** The earlier case considers the broad adult/service relationship, including one failed-send example with an unknown cause. This case does not reuse that string or scenario. It develops error-state and recovery review across validation, read-only reload, generation availability, session expiry, partial import, permissions and incomplete AI assistance. Its Keep example shows why a clear constraint should survive tone editing.

## Review method

1. Map each message to a declared state in the evidence register.
2. Separate the observed condition from inferred cause or personal fault.
3. Identify what completed, what did not and what remains editable.
4. Check that the next action can change the relevant condition.
5. Review naturalness, terminology, responsibility, warmth, dignity and proportionality.
6. Classify Improve, Resolve or Keep; prioritize consequential misunderstanding qualitatively.
7. Reconcile the revisions as one set, keeping action labels and state terms consistent.
8. Leave unknown product behaviour open for owner confirmation and later in-context review.

## Evidence demonstrated

- Eight traceable fictional state assumptions and eight structured findings.
- Separation of user-correctable validation from unavailable system operations.
- Japanese revisions with practical English explanations.
- Partial-completion and retry-prerequisite reasoning.
- A deliberate unresolved recovery route, rather than reassuring invention.
- A Keep decision that preserves useful directness.
- A summary and owner-question queue suitable for a real review discussion.

The evidence is the documented analysis and its traceability. It is not an executed test suite, benchmark, privacy audit or independent validation.

## Scope and limitations

This AI-assisted fictional portfolio case is not client work, a legal/compliance assessment, psychological or medical advice, or an evaluation of a named AI model. No real company practices or user responses are asserted.

No English source was provided, so bilingual translation fidelity was not assessed. Implemented behaviour, accessibility, retained data and timing were not tested. Tone interpretations depend on audience, relationship and screen context; different products may need different wording. Real use requires product-owner confirmation and review in the actual interface.

**Numbering:** ClearJP Case #007 is part of the ClearJP series, separate from the repository's other evaluation cases.

