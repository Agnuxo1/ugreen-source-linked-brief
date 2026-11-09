# Evidence contract

The following are required output concepts, not claims about an undocumented CLI JSON schema. Map only actual returned expert fields; use "not returned" for missing values. Never manufacture them.

## Run summary

Show the user's exact question, authorized document scope, considered source count, omitted sources and reasons, evidence coverage, source-change status, and whether the result is an unsaved preview or a verified saved file. Do not publish private source contents outside the device.

## Source ledger

For every usable source record its actual path or file ID, returned metadata, verified SHA-256 when available, observed version label if explicitly present in content, extraction/recheck status, and returned coverage. A name or modification time does not prove semantic authority. Unknown fields remain unknown. Partial extraction and changed-source warnings are visible next to affected claims.

## Claim ledger

For each brief claim, show its text, actual source identity, source version/hash status, and the returned page/section locator or a short source excerpt. If only an excerpt is returned, label it as an excerpt and do not invent pagination. Preserve units and dates. Separate a source's assertion from independently established truth; this workflow does not independently verify the source's truth.

Disagreeing versions occupy separate rows with the same topic label. Do not average different figures or select the newest-looking filename. If the user has not chosen an authoritative version, say so. Unsupported candidate claims are excluded from the factual brief and listed as unanswered questions or gaps.

An empty result yields no factual brief. If at least one source is usable and the user permits a partial brief, label the result PARTIAL and enumerate all omissions. A changed or unrecheckable version invalidates its dependent claims until the user resolves it. Do not count a source twice to inflate coverage. Record save verification separately from document evidence quality.
