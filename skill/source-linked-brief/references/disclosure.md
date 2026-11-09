# Development and component disclosure

The source-linked-brief Skill and its core workflow were newly written on 9 November 2026 for the UGREEN Hackathon 2026. No previously developed Skill or prior submission package was reused. The general problem of source-aware summarization is not claimed as a new invention.

New principal functionality consists of a bounded three-expert workflow; a claim/source/version ledger; explicit disagreement and missing-evidence handling; source-version rechecks; and an optional, separately approved save. The package contains only original Markdown instructions and references. No executable runtime, pretrained weights, external dataset or private NAS documents are bundled.

## Official UGREEN resource

UGOS Skill Creation Tool / Uliya Skill Kit 0.7.3, public catalog 2.0.0 and official technical documentation were used to author the orchestration and check its structure. Source: https://ai.ugreen.com/pages/hackathon-starter-kit . The kit ZIP SHA-256 is cf557e5a022e4297892f39768132855154232efdedeb726b2845450ccd70e1b3. The kit's JavaScript checker and capability catalog are development tools only and are not redistributed in this submission. Their use is governed by the official SkillHub user agreement, privacy policy, content/publication requirements and hackathon rules accepted by the entrant. No open-source license for the vendor kit is asserted.

## AI assistance

OpenAI Codex assisted concept development, original Markdown drafting, catalog mapping, static validation, proposal preparation and review. Independent AI review was used for error finding, with serious findings checked against sources. JEV advised workflow routing. AI-generated instructions remain the entrant's responsibility. No AI model weights or third-party training data are included; target model choice and behavior remain unverified until NAS testing.

## Proposal build tools

The separate proposal PDF uses ReportLab (BSD-3-Clause, https://github.com/MrBitBucket/reportlab-mirror) for layout and pypdf (BSD-3-Clause, https://github.com/py-pdf/pypdf) for local inspection. They are authoring tools, not dependencies of the Skill, and their code is not included. The PDF uses standard base fonts. Installed versions and PDF checks are recorded in private build evidence, not represented as NAS results.

## Current validation boundary

The Skill is a Round 1 pre-test package. Static checks establish document/package conformance only. Installation, configured local-model availability, exact expert result schemas, permission enforcement, extraction quality, version-race handling and save semantics require validation on the assigned NAS. No operational NAS demonstration, measured summarization improvement, official evaluation score or award is claimed.
