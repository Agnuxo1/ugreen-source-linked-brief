---
license: other
license_name: ugreen-submission-original-materials
license_link: LICENSE
pretty_name: Source-Linked Brief - reviewed source archive
tags:
- documentation
- retrieval-augmented-generation
- ai-nas
---

# Source-Linked Brief

A source-and-version ledger for concise NAS document briefs, with visible disagreements, evidence gaps and approved saving.

This repository preserves the original Round 1 Skill package and proposal submitted to [UGREEN Hackathon 2026 on AI NAS](https://ugreenhackathon.devpost.com/) on 9 November 2026. Devpost confirmed receipt of submission **1291317**: [project page](https://devpost.com/software/source-linked-brief). Jury evaluation, selection, score, rank and awards are unknown.

The new Skill and core workflow were authored on 9 November 2026. They describe a bounded workflow over up to ten documents explicitly selected by the user. The file, document and knowledge experts return a brief, a claim/source/version ledger, disagreements and evidence gaps. Saving requires approval and the workflow rechecks source identity. This archive contains Markdown instructions and a proposal; it contains no application server, trained model or training dataset.

<!-- impact-note:start -->
<sub><strong>Efficiency and practical value.</strong> The proposed workflow bounds each brief to ten selected documents and keeps claims tied to their source and version. This is designed to reduce repeated document searching and make disagreements easier to resolve before a brief is saved. Static package checks are complete; time savings and extraction quality still require device testing. See the <a href="skill/source-linked-brief/references/validation-plan.md">validation plan</a>.</sub>
<!-- impact-note:end -->

## Contents

| Path | Purpose |
| --- | --- |
| `skill/source-linked-brief/SKILL.md` | Native Skill, including exact expert delegation mappings |
| `skill/source-linked-brief/references/` | Evidence contract, prospective validation, disclosure and authorship |
| `artifacts/source-linked-brief-round1-v1.zip` | Exact submitted five-Markdown package |
| `artifacts/Source_Linked_Brief_UGREEN_Round1_v2.pdf` | Exact submitted two-page proposal |
| `MANIFEST.json` | SHA-256 and byte length for every other payload file |

The ZIP is **8,898 bytes**, with five Markdown files totaling **18,471 uncompressed bytes**. The proposal is **7,062 bytes** and contains ten answers totaling **349 words**; headings bring the answer section to 373 words. Neither contact information nor authenticated submission receipts are published here.

## Validation and scope

The original checker from official Uliya Skill Kit **0.7.3**, using capability catalog **2.0.0**, returned **static-pass, zero errors and zero warnings**. Independent checks verified ZIP/source equality, direct reference links, the proposal text and limits, checker identity and rejection of three deliberately invalid package copies. PDF metadata was corrected before submission; its visible text and rendered pages remained identical to the reviewed original.

These results establish static package conformance. **No NAS runtime, installation, extraction quality, summarization accuracy, model behavior or successful save has been demonstrated for this Skill.** Two core cases and one permission/hostile-content edge case are specified prospectively in [the prospective validation plan](skill/source-linked-brief/references/validation-plan.md) for device validation if selected. They are not reported as completed experiments.

The Skill uses capabilities described by the official UGOS/Uliya kit. Obtain current vendor instructions from the [official starter kit](https://ai.ugreen.com/pages/hackathon-starter-kit) and check the applicable agreements and device access before use. Vendor scripts, capability catalogs, accounts, credentials, private documents, model weights and private operational evidence are excluded from this archive. OpenAI Codex assisted drafting, capability mapping and checks; review findings were checked against evidence.

## Research background

Francisco's earlier work provides context for this design:

- [Unified-Holographic-Neural-Network](https://github.com/Agnuxo1/Unified-Holographic-Neural-Network), a research line begun in 2024: persistent document indexing, exact source coordinates, learned query-to-passage associations and checked reversible memory export.
- [ASIC-RAG-CHIMERA](https://github.com/Agnuxo1/ASIC-RAG-CHIMERA): content-addressed storage for RAG.
- [CAJAL RAGFlow connector](https://github.com/Agnuxo1/cajal-ragflow-connector): retrieved chunks connected to local-model document generation.

These are background references. Their code and old submission materials are not bundled or reused as this new UGOS Skill, and their published experiments are not performance results for this package.

## Authorship and rights

Copyright (c) 2026 **Francisco Angulo de Lafuente**. ORCID: [0009-0001-1634-7063](https://orcid.org/0009-0001-1634-7063).

Independent AI researcher. Earlier research at ECOFA concerned biotechnology for clean energy and microbiological processing of organic waste into second-generation biofuels. Historical Spanish patents **ES 2273594 B1** and **ES 2341194 B1** document that earlier work; both have lapsed and are not represented as active patents or as protection for this Skill. This background is attribution, not evidence of the package's performance.

Original materials remain the author's property, subject to the non-exclusive evaluation and publicity permissions in the official competition rules. All other rights are reserved. Public availability does not grant an additional open-source or third-party data license. See [LICENSE](LICENSE), [CITATION.cff](CITATION.cff) and the package's [author-rights notice](skill/source-linked-brief/references/author-rights.md).

## Names used in the development record

**JEV** names the external service used to route planning and review decisions during development. **ECOFA** identifies the author's earlier clean-energy biotechnology work described above.

<!-- author-background:start -->
## Author background

**Francisco Angulo de Lafuente**, independent AI researcher · [ORCID](https://orcid.org/0009-0001-1634-7063) · [arXiv](https://arxiv.org/a/angulodelafuente_f_1.html) · [Google Scholar](https://scholar.google.com/citations?user=6nOpJ9IAAAAJ) · [ResearchGate](https://www.researchgate.net/profile/Francisco-Angulo-Lafuente-3) · [Figshare](https://figshare.com/authors/Francisco_Angulo_de_Lafuente/22601234) · [Wikipedia](https://es.wikipedia.org/wiki/Francisco_Angulo_de_Lafuente)

Earlier research at ECOFA focused on biotechnology for clean energy and on second-generation biofuels obtained by microbiological processing of organic waste. Two Spanish patents document that work:

- **ES 2273594 B1**, *Process for obtaining fuels from organic waste*. Filed 5 September 2005, grant published 16 February 2008. [OEPM](https://www.oepm.es/pdf/ES/0000/000/02/27/35/ES-2273594_B1.pdf) · [Google Patents](https://patents.google.com/patent/ES2273594B1/en)
- **ES 2341194 B1**, *Method for obtaining paraffin by a biological process with microorganisms from organic matter, and its refining for use as fuel*. Filed 11 September 2007, grant published 26 April 2011. Also published as EP2196519 and WO2009034217. [OEPM](https://www.oepm.es/pdf/ES/0000/000/02/34/11/ES-2341194_B1.pdf) · [Google Patents](https://patents.google.com/patent/ES2341194B1/en)

These are historical publication and grant records under the inventor name Francisco Angulo Lafuente, and both have since lapsed. They are cited as evidence of a research trajectory and make no statement about current enforceability.
<!-- author-background:end -->
