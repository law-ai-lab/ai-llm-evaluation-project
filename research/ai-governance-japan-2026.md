# AI Governance in Japan — 2026

**Independent research by Rie Nakahara · Official-source review: 22 October 2026 (UTC)**

> This document is an independent study project for educational and portfolio purposes. It is not legal advice. AI laws, regulations and guidance continue to evolve, so current official sources should be checked before making compliance decisions.

## Why I researched this

Completing **ITU Academy — AI Governance: Fundamentals**, including its five modules on governance, bias and accountability, data governance, regulation, and ethics, prompted a question: how can similar AI receive different treatment across jurisdictions and uses?

This report is my subsequent independent investigation of Japan. It does not reproduce course lessons, slides, PDFs or assessment materials, and does not imply ITU endorsement. Research and drafting were AI-assisted; the examples and practical evaluation proposals below are portfolio analysis, not client work or completed audits.

## Executive Summary

- Japan combines an AI promotion statute, national policy, voluntary governance guidance, technical evaluation resources and existing sectoral laws. Calling this simply “no regulation” or “only soft law” misses important layers. The AI Act became fully effective on 1 September 2025. [S1]
- The current policy snapshot includes the **Second AI Basic Plan, 14 July 2026**, Business Guidelines **v1.2, 31 March 2026**, government procurement/use guidance **v2.0, 12 June 2026**, and AISI evaluation guidance **v1.20, 7 July 2026**. [S2], [S4], [S5], [S6]
- A legal obligation, a government internal rule and a recommended evaluation practice are different things. Each needs its own scope and evidence.
- A model's deployment context matters: drafting information, recommending a consequential decision and executing that decision create different risks. Jurisdiction is more than an individual's residence. See Sections 7–8.
- My practical conclusion: governance becomes useful when it produces testable requirements, named owners, documented evidence and a way to correct failures.

## 1. What AI Governance Means

For this report, governance means how an organization decides whether and how to develop, procure, deploy, monitor and retire AI, and who answers for its effects. This is a working definition, not a quotation or a statutory definition.

It connects three questions: **What applies? Who decides? What evidence shows the system is suitable for this use?** An accurate model can still be deployed in an unsuitable workflow; a policy can exist without anyone testing whether the promised safeguard works. These are analytical distinctions used throughout this report.

## 2. Japan's Current AI Governance Framework

| Layer | Current instrument or institution | Function and status |
|---|---|---|
| National legislation | Act on Promotion of Research and Development, and Utilization of AI-related Technology, Act No. 53 of 2025 | Binding statute establishing a promotion/governance framework, responsibilities, a Basic Plan and AI Strategic Headquarters. [S1] |
| National strategy | Second AI Basic Plan, Cabinet decision, 14 July 2026 | Government policy covering deployment, development capabilities, governance and an AI-powered society. It supersedes the first December 2025 plan as the current plan. [S2] |
| Cross-cutting appropriateness guidance | AI Strategic Headquarters guideline, 19 December 2025, under Article 13 | Encourages voluntary, proactive, proportionate stakeholder action; legal basis does not turn every recommendation into a penal obligation. [S3] |
| Business implementation | MIC/METI AI Guidelines for Business v1.2 | Non-binding business guidance addressing developers, providers and business users. [S4] |
| Central-government procurement/use | Digital Agency guidance v2.0, DS-920 | Normative rules within the government's information-system framework, including governance and risk assessment. Not a general private-sector statute. [S5] |
| Safety evaluation | Japan AI Safety Institute, AISI | Technical evaluation perspectives and example test items, including agent-system risks in v1.20. [S6] |
| Existing law | APPI, copyright, competition, civil law and sectoral regulation | Applies according to the relevant activity, actors, data, harm and sector. Sections 6–8 identify examples. |

The AI Act's official outline describes information collection, investigation of rights-infringing cases, guidance/advice and communication of findings, alongside promotion. It also describes business cooperation as an **endeavour**, rather than an unrestricted mandatory disclosure power. This framework should not be equated with the EU's high-risk conformity-assessment regime. [S1]

## 3. Japan's Regulatory Philosophy

The best description is a **combination**, with evidence for each element:

| Description | Evidence | Interpretation |
|---|---|---|
| Promotion and innovation oriented | The Act and current Basic Plan put development and deployment alongside risk response. [S1], [S2] | Risk management is intended to support adoption, not merely prohibit uses. |
| Principles based | Article 13 guidance identifies human-centricity, fairness, safety, transparency and accountability among its main elements. [S3] | Principles need translation into operational decisions. |
| Risk proportionate | The same guidance considers stakeholder position, scale, purpose and risk. [S3] | Different uses need different controls; this is not a universal statutory tier list. |
| Soft-law oriented in cross-sector business governance | Business Guidelines are non-binding soft law. [S4] | Existing binding laws still matter. |
| Agile and adaptive | The July 2026 Basic Plan explicitly discusses responsible agile governance, combining institutional, technical and organizational responses. [S2] | Governance should be revisited as systems, uses and evidence change. |

These descriptions are my synthesis of the instruments, not a claim that every Japanese regulator applies one identical method.

## 4. Binding Law vs Voluntary Guidance

**Classification rule:** read the issuer, legal basis, addressee, wording and consequences before treating a sentence as a requirement.

- **Binding law:** the AI Act and applicable existing legislation. Their provisions have different subjects and legal effects; a promotion duty, a prohibition and an enforcement power are not interchangeable. [S1], [S7]
- **Government policy:** the AI Basic Plan sets national direction; it is not itself a private company's certification checklist. [S2]
- **Voluntary guidance:** the Article 13 guideline and Business Guidelines guide stakeholder conduct. A statutory foundation and voluntary implementation can coexist. [S3], [S4]
- **Government administrative rules:** DS-920 is explicitly normative for the government information-system context. It provides for ministry/agency Chief AI Officers and escalation of potentially high-risk projects. Its “high-risk” assessment is not an EU legal classification. [S5]
- **Technical guidance:** AISI supplies evaluation perspectives, not proof that a product is legally compliant or safe in all circumstances. [S6]
- **Enacted but awaiting implementation / developing measures:** Japan's July 2026 APPI amendment is enacted, but most provisions commence on a Cabinet Order date within two years of promulgation. Implementing rules and commencement must be checked provision by provision. Do not label the entire amendment merely proposed—or assume it is entirely operational. [S8]
- **Author analysis:** the test plans, Japanese examples and checklist below are proposed working practices, not additional Japanese legal mandates.

Contracts or procurement conditions can also make particular deliverables important in a specific engagement; that needs the actual agreement, not an inference from a guidance title.

## 5. AI Safety and Evaluation

AISI's July 2026 guide expands evaluation perspectives and example items for AI agents. Its examples address harmful output, misinformation, fairness/inclusion, privacy, security, explainability, robustness, data quality and verifiability, plus observation/control of autonomous behaviour and interaction with external environments. For example, agent evaluation considers control over high-risk actions such as file changes and permission escalation. [S6]

**My evaluation proposal:** assess the deployed system, including retrieval, interfaces and tool permissions, rather than reporting a model benchmark as the whole safety case. Record the version, inputs, expected behaviour, observed failures, severity, mitigation and retest result. An agent that answers safely but executes an unauthorized action needs a different test from a text-only assistant.

Human oversight should be tested as a workflow: can a reviewer see the relevant evidence, understand uncertainty, stop the action and correct the outcome? A person clicking “approve” is not evidence that these conditions hold. This is a practical recommendation, not a claim that Japan universally mandates a particular approval interface.

## 6. Privacy, Data Governance, Copyright and Other Existing Law

### Personal information

APPI and its implementing guidance remain a separate layer from AI policy. PPC's generative-AI warning asks businesses to check that personal-information prompts remain within the identified utilization purpose, and whether a provider uses personal data beyond producing the response, including model training. It warns that the latter can raise violations when consent has not been obtained. This is not a blanket rule that all AI processing requires consent. [S7], [S9]

The **17 July 2026 amendment announcement** distinguishes enactment from commencement and anticipates implementing regulations/guidelines. This report does not treat future exceptions as permission to upload customer, candidate or patient data today. [S8]

**Practical analysis:** map input, retrieval, output, logs, subprocessors and onward transfers. Check retention, training use, access and deletion against current legal advice and actual vendor terms. “Training disabled” alone does not establish that every other data-handling question is resolved. Use lawful, minimized data for subgroup evaluation too.

### Copyright

The Agency for Cultural Affairs' March 2024 understanding and July 2024 checklist explain the relationship between AI and copyright. They are interpretive/guidance materials, not a new AI-specific copyright licence or a binding court judgment. [S10]

Its discussion of Article 30-4 does not justify “anything online may be used for AI.” The purpose and conditions of the use, including the rights-holder-interest proviso, matter; generation/use of an output raises distinct questions such as similarity and reliance. [S11]

**Practical analysis:** separate training, retrieval, prompted reproduction and publication. Keep provenance and licensing evidence; escalate suspicious reproduction. Do not promise that generated text is automatically infringement-free.

### Competition

JFTC's **Report Regarding Generative AI v2.0, 16 April 2026**, updates its market study and reorganizes Antimonopoly Act issues. The report says JFTC will address problematic conduct under the Act. A market-study concern is not itself a finding that a particular company has broken the law. [S12]

**Practical analysis:** examine vendor dependence, data access, switching and contractual restrictions when choosing infrastructure. Competition assessment and model-quality evaluation answer different questions.

### Civil and product liability

Contractual non-performance and tort are relevant starting points for harm analysis under Civil Code Articles 415 and 709; liability still depends on the applicable elements and facts. The official English translation is a reference translation, not a substitute for current Japanese law. [S13]

Consumer Affairs Agency guidance distinguishes standalone software, which is intangible and outside the Product Liability Act's product definition, from manufactured products incorporating software, which can fall within it. “AI caused harm” therefore does not automatically establish a Product Liability Act claim—or eliminate other liability. [S14]

## 7. Japan vs EU vs United States

| Jurisdiction | Governance emphasis | What an evaluator should establish |
|---|---|---|
| Japan | Promotion statute/policy, proportionate stakeholder guidance, technical evaluation and existing laws. [S1]–[S6] | Relevant sector/data law, organizational responsibility and appropriate evidence for the use. |
| EU | Binding AI Act: prohibited practices, high-risk classification, specific transparency obligations and separate general-purpose-model rules. High-risk controls include an ex-ante compliance structure. [S15]–[S20] | Actor role, territorial scope, intended purpose, classification, applicable obligations and commencement date. |
| US | Federal sectoral/agency law, voluntary NIST risk management and state/local rules. FDA device oversight, California employment rules and NYC hiring-tool rules illustrate different layers. [S21]–[S25] | Sector, state/local reach, covered activity and applicable law; voluntary RMF use does not replace legal analysis. |

NIST AI RMF 1.0 is voluntary. Its core functions are **[Govern, Map, Measure, Manage](https://airc.nist.gov/airmf-resources/airmf/5-sec-core/)**; a generative-AI profile was released in July 2024. NIST's current page says the framework is being revised, so a future revision should not be represented as already final. [S21]

California's automated-decision employment regulations took effect on **1 October 2025**, clarifying application of existing antidiscrimination rules. NYC's narrower AEDT regime requires, where applicable, a recent bias audit, public audit information and notices. These examples refute “the US is unregulated”; they are not a survey of every US jurisdiction or current federal enforcement priority. [S24], [S25]

### EU categories and dates need separate checks

Article 5 prohibits specified practices; Article 6 and Annex III identify high-risk systems subject to conditions and exceptions. Article 50 imposes transparency duties for certain interactions and synthetic content. These are not mutually exclusive labels for every model, and “experimental” is not a universal exemption. [S15]–[S18]

The Commission's current timeline incorporates the **AI Omnibus, effective 27 July 2026**: prohibitions began applying in February 2025, general-purpose-model rules in August 2025, and the majority of rules in August 2026. Annex III high-risk requirements now apply from **2 December 2027**, and the Annex I product route from **2 August 2028**. Transitional exceptions still need checking. Older summaries giving August 2026 as the blanket high-risk deadline are unsuitable for this snapshot. [S19], [S20]

### Jurisdiction is more than residence

EU AI Act Article 2 includes providers placing systems/models on the EU market and, in specified circumstances, providers/deployers outside the EU whose system output is used in the EU. A Japanese developer therefore cannot determine applicability solely from its office address or the nationality of one user. [S26]

**My scoping questions:** where is the product offered/deployed; who provides and operates it; what decisions does it influence; who is affected; what data crosses borders; and which sectoral or extraterritorial rules apply? Residence can matter under particular rules, but it is only one fact.

## 8. Same AI, Different Governance: Use Cases

Both examples are fictional analytical scenarios. They illustrate questions to resolve, not definitive classifications or deployment approvals.

### Example 1 — A language model used in healthcare

| Use of a similar model | Japan: governance question | EU / US comparison | Proposed evaluation evidence |
|---|---|---|---|
| General wellness information, without patient-specific diagnosis | Does intended purpose/function remain outside the medical-device boundary? A wellness label cannot settle actual functionality. | Medical-device status and AI Act duties require separate checks; not every health-related chatbot is automatically high-risk. | Unsupported health claims, escalation language, uncertainty, readable Japanese and privacy tests. |
| Clinical decision support for professionals | Does the function support diagnosis/treatment and pose relevant health risk? Professional involvement alone does not settle device status. | US law excludes certain CDS functions from the device definition when statutory conditions are met; FDA's January 2026 guidance explains that boundary. | Source traceability, evidence presentation, conflicting inputs, omissions and whether clinicians can independently review the basis. |
| Patient-specific diagnosis or treatment recommendation | Resolve medical-device applicability and the relevant regulatory route before release. | EU Article 6(1)'s product route depends on Annex I coverage and required third-party assessment; US device oversight remains relevant to device functions. | Clinically appropriate validation design, harmful-error analysis, population coverage, change control and effective intervention. |

**Official anchors:** Japan's medical-software guidance considers medical intended purpose and potential effect on life/health; low-risk excluded functions require their own assessment. [S27] FDA distinguishes non-device CDS from device functions, including functions for patients/caregivers. [S22] The EU product route is conditional, not “all medical AI is high-risk.” [S16]

**My conclusion:** the model name does not resolve the regulatory question. The interface, user, claims, output and reliance on it change what must be demonstrated. No model benchmark alone establishes clinical suitability.

### Example 2 — An assistant used in recruitment

| Workflow | Japan: proposed risk review | EU / US comparison | Proposed evaluation evidence |
|---|---|---|---|
| Draft a job description, reviewed before publication | Check accuracy, stereotypes and whether criteria are relevant to the role. | Drafting is not automatically the same as candidate selection; assess actual function, including any targeted-advertising use. | Compare drafts against approved requirements; test exclusionary language. |
| Rank applicants for recruiter review | Review candidate-data handling, proxy criteria, job relevance and how ranking influences decisions. | EU Annex III covers specified recruitment/selection uses; Article 6 exceptions require careful assessment. California employment rules and NYC AEDT rules may apply according to their scope. | Comparable-profile tests, subgroup error/selection rates, missing-data behaviour and reasons traceable to evidence. |
| Automatically reject applicants | Treat loss of opportunity and inability to challenge errors as substantial governance risks; resolve accountability and intervention before deployment. | Automation does not escape the same employment rules. Human review also does not automatically remove high-risk status or other duties. | False rejections, threshold sensitivity, accommodation paths, appeal routing and demonstrated override capability. |

**Official anchors:** MHLW's fair-recruitment guidance emphasizes human rights and job-relevant aptitude/ability; it is not cited here as a new AI-specific audit statute. [S23] EU recruitment/filtering/evaluation uses appear in Annex III, subject to Article 6. [S16], [S17] California and NYC are examples of binding employment-related rules, not universal US audit requirements. [S24], [S25]

**My conclusion:** recommending a rank can already materially affect access to work. Assess the decision pathway rather than assuming “a human remains involved” resolves fairness or responsibility.

## 9. What This Means for AI Quality and Evaluation Work

The following is my proposed translation from governance questions into QA deliverables. It draws on AISI's evaluation approach and NIST's risk-management structure; it is not a legally prescribed Japanese checklist. [S6], [S21]

| Governance question | Evaluation / QA task | Reviewable evidence |
|---|---|---|
| Is the output supported? | Claim-level hallucination tests, source checking, unknown-answer and conflicting-evidence cases | Annotated failures, source dates, severity and correction/retest records |
| Are people treated fairly? | Comparable inputs and lawful subgroup evaluation; inspect proxies and small-sample uncertainty | Test design, group coverage, error patterns and unresolved limitations |
| Can someone understand and contest the result? | Check explanation fidelity and escalation/override workflow | Evidence-to-decision trace and a completed intervention exercise |
| Is data handled as intended? | Synthetic-data leakage probes, retrieval isolation and logging/access checks | Data-flow map and documented access/retention findings |
| Can misuse or attacks change behaviour? | Red teaming, Japanese prompt injection, harmful requests and agent-permission tests | Reproducible attack cases and mitigations |
| Does deployment remain suitable? | Versioned regression tests, drift/complaint monitoring and incident exercises | Monitoring thresholds, named owner, incident log and rollback record |
| Can a later reviewer reconstruct the decision? | Preserve proportionate test configuration and decision records | Model/prompt/retrieval versions, approvals and residual-risk rationale |

### What this means for an AI Quality / Evaluation professional in Japan

A useful contribution is to turn an uncertain concern into a bounded, reproducible question: what might fail, for whom, under what conditions, how serious would it be, and what evidence would change the release decision?

For a portfolio, this means showing a test brief, risk assumptions, rubric, evidence-linked findings, prioritization and retest plan. It does not mean claiming legal expertise, certification or an audit that was never performed. Legal and domain specialists resolve legal applicability and clinical or employment validity; evaluators make behaviour and limitations visible.

## 10. Japanese-Language and Localization Risks

**Author analysis and proposed tests:** these are quality/governance risks, not claims of a universal statutory Japanese-language standard. They operationalize attention to human-centricity and inclusion without pretending one wording test proves legal compliance. [S3]

| Fictional issue | Why it matters | Practical review |
|---|---|---|
| An uncertain suggestion becomes 「必ず改善します」 | Translation invents certainty. | Compare modality and evidence against the source. |
| 「こちらで対応いたします」 in an automated assistant | Politeness can leave the actor and promised action unclear. | Identify whether AI, a human team or the user acts, and when. |
| Long sentences, double negatives and abstract katakana | Older adults or users with limited familiarity may struggle; do not assume a test outcome. | Plain-language review, clear subjects and explicit next steps; involve intended users where feasible. |
| A refusal sounds dismissive or a chatbot implies intimate human understanding | A fluent answer can undermine dignity or foster misplaced trust. | Assess warmth, respect, boundaries and truthful identity together. |
| Japanese disclosures omit a condition present in the approved source | Users may misunderstand data use or a consequential choice. | Check semantic completeness, UI context and whether the described choice actually exists. |
| English-only safety tests are reused without Japanese cases | Language coverage remains unproven. | Include Japanese, mixed-language inputs, ellipsis, ambiguous subjects, names and honorifics. |

For example, changing 「診断結果です」 to 「参考情報です」 does not make diagnostic functionality non-medical. Wording, behaviour and the intended purpose must be reviewed together. This is a proposed QA safeguard, not a classification opinion.

## 11. Practical Deployment Checklist

### Before deploying an AI system in Japan

**Proposed working checklist—not a compliance certificate.** Record an owner and supporting evidence for each answer; unresolved critical questions should trigger specialist review.

- [ ] Define intended users, intended use, prohibited uses and actual decision influence.
- [ ] Identify effects on rights, health, employment, finance, education or public-service access.
- [ ] Map provider/operator roles, deployment locations, affected people and cross-border reach.
- [ ] Identify current Japanese laws, sectoral rules, contracts and relevant guidance; distinguish their legal status.
- [ ] Check commencement dates and document which version of each instrument was used.
- [ ] Map data sources, personal/sensitive information, purposes, relevant consent/exceptions, transfers, retention and vendor training use.
- [ ] Assign accountable owners, escalation routes and release authority.
- [ ] Demonstrate human review, stop/override and correction routes appropriate to consequences.
- [ ] Evaluate reliability, hallucinations, bias/fairness and relevant user groups; disclose coverage limits.
- [ ] Test Japanese meaning, clarity, tone, accessibility and disclosures in interface context.
- [ ] Test adversarial inputs, retrieval boundaries and agent-tool permissions.
- [ ] Define monitoring, incident/complaint records, rollback and retesting after changes.
- [ ] Have legal/domain specialists resolve applicability and any reporting duties; do not invent a universal AI incident-reporting deadline.

## 12. Key Takeaways

My main finding is that “Which model?” is an incomplete governance question. **“Which system, doing what, for whom, under whose responsibility, with which evidence?”** is a more useful starting point.

Japan's approach connects promotion, principles, proportionate governance and existing law. An evaluator's opportunity is to make those principles observable in product behaviour, including Japanese-language behaviour—not to relabel recommendations as law.

### Uncertainties and limits

- Legal applicability, device status and individual liability require facts and specialist judgment. The fictional scenarios are not authoritative classifications.
- APPI amendment commencement and implementing materials, AI guidance revisions and EU transitional provisions need fresh checks before a real decision. [S8], [S19]
- Copyright guidance is not a definitive resolution of every training/output dispute. [S10], [S11]
- US coverage here is deliberately selective. It does not establish a complete federal/state compliance position or describe every changing enforcement priority.
- Some official pages/PDFs could not be fully retrieved: METI's v1.2 publication was verified through its official indexed listing and the Cabinet Office cross-reference, but this report does not assert specific newly added v1.2 clauses. EUR-Lex returned a verification wall; EU substantive checks used the Commission's official Service Desk and July 2026 amendment announcement instead.
- No user testing, model evaluation, privacy audit, legal review, client results or independent validation was conducted for this study. The evaluation tables are proposals.

### Research method and exclusions

I inspected the existing repository and separated this research from the numbered ClearJP demonstrations. I prioritized current official publication hubs, checked instrument type and dates, distinguished enactment from commencement, and compared official source text against each major factual claim. Interpretations and proposed tests are labelled above. Links were checked for a relevant official destination; access limitations are recorded rather than treated as successful full-text retrieval.

I excluded unsupported claims of Japanese blanket AI certification, universal human-approval requirements, a universal AI incident deadline, “all training is copyright-free,” “all medical AI is EU high-risk,” and “the US is unregulated.” I also excluded speculative outcome metrics, paid standards text, and all proprietary ITU course content.

## Sources

Official primary sources only. Dates are publication/decision dates where stated; undated hubs were checked on 22 October 2026 (UTC). English government translations may be provisional/reference translations. The cited legal text and its current Japanese or EU official version take precedence over this report.

[S1]: https://www8.cao.go.jp/cstp/ai/ai_act/ai_act.html
[S2]: https://www8.cao.go.jp/cstp/ai/ai_plan/ai_plan.html
[S3]: https://www8.cao.go.jp/cstp/ai/ai_guideline/ai_gl_eng_20260116.pdf
[S4]: https://www.meti.go.jp/shingikai/mono_info_service/ai_shakai_jisso/20260331_report.html
[S5]: https://www.digital.go.jp/news/decb64eb-f26e-41cb-8d37-f3dd173108b8
[S6]: https://aisi.go.jp/output/output_framework/guide_to_evaluation_perspective_on_ai_safety/
[S7]: https://www.ppc.go.jp/personalinfo/legal/
[S8]: https://www.ppc.go.jp/news/press/2026/260717/
[S9]: https://www.ppc.go.jp/files/pdf/230602_kouhou_houdou.pdf
[S10]: https://www.bunka.go.jp/seisaku/chosakuken/aiandcopyright.html
[S11]: https://www.bunka.go.jp/seisaku/bunkashingikai/chosakuken/pdf/94037901_01.pdf
[S12]: https://www.jftc.go.jp/en/pressreleases/yearly-2026/April/260416.html
[S13]: https://www.japaneselawtranslation.go.jp/en/laws/view/3494/en
[S14]: https://www.caa.go.jp/policies/policy/consumer_safety/other/pl_qa.html
[S15]: https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-5
[S16]: https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-6
[S17]: https://ai-act-service-desk.ec.europa.eu/en/ai-act/annex-3
[S18]: https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-50
[S19]: https://ai-act-service-desk.ec.europa.eu/en/ai-act/timeline/timeline-implementation-eu-ai-act
[S20]: https://digital-strategy.ec.europa.eu/en/news/ai-omnibus-enters-force
[S21]: https://www.nist.gov/itl/ai-risk-management-framework
[S22]: https://www.fda.gov/regulatory-information/search-fda-guidance-documents/clinical-decision-support-software
[S23]: https://kouseisaiyou.mhlw.go.jp/basic.html
[S24]: https://calcivilrights.ca.gov/2025/06/30/civil-rights-council-secures-approval-for-regulations-to-protect-against-employment-discrimination-related-to-artificial-intelligence/
[S25]: https://www.nyc.gov/site/dca/about/automated-employment-decision-tools.page
[S26]: https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-2
[S27]: https://www.mhlw.go.jp/content/11120000/001082227.pdf

| Ref. | Title / issuing organization | Date / status |
|---|---|---|
| [S1] | AI Act publication hub — Cabinet Office; linked official overview and e-Gov statute | Promulgated 4 June 2025; fully effective 1 September 2025; binding law |
| [S2] | Artificial Intelligence Basic Plan — Cabinet Office / Cabinet | Second plan, 14 July 2026; government policy. [English text](https://www8.cao.go.jp/cstp/ai/ai_plan/aiplan_eng_20260714.pdf) |
| [S3] | Guideline for Ensuring Appropriateness of AI R&D and Utilization — AI Strategic Headquarters | 19 December 2025; voluntary stakeholder guidance under Article 13; provisional English translation |
| [S4] | AI Guidelines for Business v1.2 — MIC/METI | 31 March 2026; non-binding guidance; direct retrieval limited. [Cabinet Office cross-reference](https://www8.cao.go.jp/cstp/ai/ai_guideline/ai_guideline.html) |
| [S5] | Government generative-AI procurement/use guideline v2.0 — Digital Agency | 12 June 2026; administrative normative guidance. [English PDF](https://www.digital.go.jp/assets/contents/node/information/field_ref_resources/decb64eb-f26e-41cb-8d37-f3dd173108b8/47764804/20260612_resources_standard_guidelines_guideline_04.pdf), Sections 1.2, 3–4 |
| [S6] | Guide to Evaluation Perspectives on AI Safety — Japan AISI | v1.20, 7 July 2026; technical guidance. [Current summary PDF](https://aisi.go.jp/assets/pdf/ai_safety_eval_summary_v1.20_ja.pdf) |
| [S7] | Laws and Guidelines — Personal Information Protection Commission | Current official APPI/implementing-guidance hub; distinguish law from explanatory guidance |
| [S8] | Promulgation of the Act Partially Amending APPI and Other Acts — PPC | 17 July 2026; enacted amendment with phased commencement |
| [S9] | Warning concerning the use of generative-AI services — PPC | 2 June 2023; supervisory/explanatory material, especially pp. 3–5 |
| [S10] | AI and Copyright — Agency for Cultural Affairs | Hub linking understanding of 15 March 2024 and checklist/guidance of 31 July 2024 |
| [S11] | General Understanding on AI and Copyright in Japan — Cultural Council subcommittee | 15 March 2024; interpretive material, not legislation |
| [S12] | Report Regarding Generative AI v2.0 — Japan Fair Trade Commission | 16 April 2026; market study / existing competition-law analysis |
| [S13] | Civil Code — Ministry of Justice, Japanese Law Translation | Reference translation; Articles 415 and 709; direct full-text retrieval limited |
| [S14] | Product Liability Act overview Q&A — Consumer Affairs Agency | Undated official explanatory page; product/software distinction |
| [S15]–[S18] | AI Act Articles 5, 6, Annex III and Article 50 — European Commission AI Act Service Desk | Official article explorer, checked 22 October 2026; binding provisions distinguished from non-binding page summaries |
| [S19] | Timeline for Implementation of the EU AI Act — European Commission AI Act Service Desk | Current timeline incorporating AI Omnibus amendments |
| [S20] | AI Omnibus enters into force — European Commission | 27 July 2026; updated 31 July. [Linked legislative text](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=OJ:L_202601744); automated text retrieval unavailable |
| [S21] | AI Risk Management Framework — NIST | RMF 1.0, 26 January 2023; GenAI Profile, 26 July 2024; voluntary; revision in progress |
| [S22] | Clinical Decision Support Software — FDA | January 2026 final guidance; interpretation of statutory non-device CDS boundary |
| [S23] | Basics of fair recruitment selection — MHLW | Undated official employment guidance |
| [S24] | Approval of employment automated-decision regulations — California Civil Rights Department | 30 June 2025 announcement; effective 1 October 2025 |
| [S25] | Automated Employment Decision Tools — NYC DCWP | Local Law 144 / rule; enforcement began 5 July 2023; official scope/FAQ linked |
| [S26] | AI Act Article 2: Scope — European Commission AI Act Service Desk | Official article explorer; checked 22 October 2026 |
| [S27] | Guideline on medical-device applicability of software — MHLW | 31 March 2021, amended 31 March 2023; boundary guidance (current text begins on PDF p. 19). [Current PMDA medical-software hub](https://www.pmda.go.jp/review-services/drug-reviews/about-reviews/devices/0048.html) for updates and consultation routes |
