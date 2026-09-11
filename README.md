# Grounded DI — September 2026 Public Record

Grounded DI LLC’s dated public archive for September 2026. This archive brings together dated public records, replay evidence, and supporting provenance. It indexes the 11 September screenshot collection and the 9 September BriefWise DI² replay release, and preserves the 8 September screenshot record.

**Operator / record owner:** Mark S. Weinstein / Grounded DI LLC  
**Initial publication:** 8 September 2026  
**Last updated:** 11 September 2026  
**Record type:** chronological public archive with linked replay artifacts, screenshots, and provenance

## 11 September — Research, replay, safety and public commentary

Ten screenshots are now preserved in the [11 September collection and gallery](records/2026-09-11/README.md), with descriptive filenames, original image bytes and an [image manifest](records/2026-09-11/IMAGE_MANIFEST.csv).

The collection covers the XT-003E Riemann ξ research checkpoint, Grounded DI OS news and replay demonstration, legal-workflow audit commentary, engineering-based AI safety, the public benchmark-audit record, and two poems. Three detail/feed pairs are retained as separate captures, not counted as separate experiments. The filename date is the archive publication date.

## 9 September — BriefWise DI² fresh local deterministic replay

**FastPath · Kernel 0.2.0 · Synthetic matter `synthetic-matter-001`**

A fresh local BriefWise kernel evaluation reproduced the saved synthetic matter’s controlled state, authorization result, canonical replay identity, and bound export manifest. The regenerated replay-identity bytes matched the original exactly. An in-memory alteration of committed content was rejected, and the untouched original passed reverification.

**Classification:** VERIFIED — FRESH LOCAL REPLAY for this saved synthetic snapshot. External independent verification remains UNVERIFIED.

### Published evidence

| Artifact | Public record |
|---|---|
| Public evidence ZIP | [BriefWise_DI2_Fresh_Local_Replay_2026-09-09_Public.zip](https://github.com/Grounded-DI/grounded-di-replay-certificate-registry/blob/0eeeabdc7c09dc607b86689027d085482e24d587/BriefWise_DI2_Fresh_Local_Replay_2026-09-09_Public.zip) |
| ZIP checksum | [SHA-256 checksum file](https://github.com/Grounded-DI/grounded-di-replay-certificate-registry/blob/0eeeabdc7c09dc607b86689027d085482e24d587/BriefWise_DI2_Fresh_Local_Replay_2026-09-09_Public.zip.sha256.txt) |
| Full release post | [BriefWise DI² GitHub post](https://github.com/Grounded-DI/grounded-di-replay-certificate-registry/blob/0eeeabdc7c09dc607b86689027d085482e24d587/BriefWise_DI2_GitHub_Post.md) |

These links are pinned to the [publication commit](https://github.com/Grounded-DI/grounded-di-replay-certificate-registry/commit/0eeeabdc7c09dc607b86689027d085482e24d587). The [replay certificate registry](https://github.com/Grounded-DI/grounded-di-replay-certificate-registry) is the canonical evidence location; this September archive provides the dated entry. Cross-posting or mirroring this release does not constitute another experiment or independent verification.

### Recorded checks

- Fresh evaluation and controlled-state reproduction: **PASS**.
- Matter, committed content, evaluation, gates, rule pack, capability profile, and source snapshot record bindings: **PASS**.
- Fresh authorization and export-manifest reproduction: **PASS**.
- Canonical replay identity and replay certificate: **PASS**, with exact byte matches.
- Complete event-chain verification from GENESIS: **PASS — 9 events**.
- In-memory committed-content tamper: **REJECTED**.
- Original files unchanged and original-state reverification: **PASS**.

Exact tamper rejection: `replay verification failed: stored evaluation diverges from fresh kernel evaluation`.

### Hashes and serialization

**Serialization:** `BW-JCS-NFC-LF-1`

**Expected and regenerated replay-identity SHA-256:**

`aa66baca6feaa5dc17aff300ded2f10591cefcdb7b6044e106741921273f0daf`

**Public ZIP SHA-256:**

`0975685e081ea67bbc2d250e2d12c1ad6a05b55126f2493735c0fafdc82cc9b7`

The replay-identity hash identifies the canonical replay record. The ZIP hash identifies the complete publication archive. They cover different bytes.

### Package contents and verification

The ZIP includes the original synthetic bundle, regenerated evaluation and authorization artifacts, replay identity and certificate, export manifest, execution provenance, report, checksums, and a standalone Python checker.

After extraction, `python3 verify_package.py` checks public file integrity, exact replay-artifact byte matches, original bundle hashes, and the nine-event hash chain. The extracted package passed this check; a deliberately altered extracted file was rejected.

The included checker does **not** execute the BriefWise rule kernel. Fresh kernel execution is documented separately in the saved report. Repeating that full evaluation requires the matching kernel and export implementation, which are not included in the ZIP.

### Scope and preservation

This is a synthetic demonstration using the existing local rule implementation. The committed sample text was manually imported. The labels `FILING_READY` and `FILING` describe synthetic kernel outputs; the capability profile has `release_capable=false`.

Underlying source-file bytes were unavailable. Their authenticity, historical authorship, external authorization provenance, and the native application’s current live storage remain UNVERIFIED. No legal correctness, real filing permission, identical model generation, private model reasoning replay, or independently implemented legal evaluation is claimed.

A personal Mac path was replaced in the public provenance copy, with the change disclosed in `PUBLICATION_NOTES.md`. Hash-bound artifacts were preserved unchanged. The package supplies a new public checksum inventory and retains the original inventory under a distinct filename. Credentials, application configuration, databases, and backups are excluded.

## 8 September — Screenshot record

### What this record preserves

The archive is intentionally narrow. It records what was publicly displayed or discussed at the time, including:

- a displayed search result and discussion referencing 20,928 deterministic results;
- a FastPath 6 Pro / Tier 20.5 working-configuration card;
- a conceptual comparison of DI-AGI and AGI work products;
- a three-run cross-thread determinism display;
- a FastPath 6 Pro replay-audit display; and
- a continuity check showing the same Protocol A control wrapper across a new model engine.

The Grounded DI position represented here is that a governed execution and evidence layer can preserve source provenance, explicit rule evaluation, state transitions, receipts, and replay evidence while the underlying model engine changes. That proposition is distinct from claiming that a base model, its weights, or every upstream generation step is deterministic.

This repository is a dated public record. It is not a new engine release, a product specification, or a standalone certification.

## Image index

| # | Business filename | Subject |
|---:|---|---|
| 1 | [2026-09-08_public-search_20928-deterministic-results.jpeg](images/2026-09-08_public-search_20928-deterministic-results.jpeg) | Public-search screenshot displaying the “20,928 Results” discussion. The count is reported as displayed in the screenshot. |
| 2 | [2026-09-08_grounded-di-os_fastpath-6-pro_tier-20-5-configuration.jpeg](images/2026-09-08_grounded-di-os_fastpath-6-pro_tier-20-5-configuration.jpeg) | Grounded DI OS screenshot showing FastPath 6 Pro and the Tier 20.5 working-configuration language. |
| 3 | [2026-09-08_public-search_di-agi-work-product_vs_agi.jpeg](images/2026-09-08_public-search_di-agi-work-product_vs_agi.jpeg) | Public-search screenshot presenting a conceptual comparison of DI-AGI work product and a theoretical AGI work product. |
| 4 | [2026-09-08_grounded-di-os_cross-thread-determinism-match.jpeg](images/2026-09-08_grounded-di-os_cross-thread-determinism-match.jpeg) | Grounded DI OS screenshot displaying a three-run cross-thread match and repeated canonical result/hash text. |
| 5 | [2026-09-08_grounded-di-replay_fastpath-6-pro_audit-record.jpeg](images/2026-09-08_grounded-di-replay_fastpath-6-pro_audit-record.jpeg) | Grounded DI OS screenshot of the FastPath 6 Pro replay-audit record, including its displayed 40/40, 2/2, and 9/9 result counts. |
| 6 | [2026-09-08_grounded-di-os_fastpath-6-pro_continuity-check.jpeg](images/2026-09-08_grounded-di-os_fastpath-6-pro_continuity-check.jpeg) | Grounded DI OS screenshot showing a continuity check for the Protocol A control wrapper across a new model engine. |

## How to read the record

A useful review separates the propositions that are often collapsed into one claim:

1. **Model capability:** what the underlying engine can generate or solve.
2. **Deterministic control:** whether a specified wrapper, rule path, or controlled workload follows the same declared procedure.
3. **Replay and provenance:** whether inputs, calculations, branches, outputs, and hashes can be preserved and checked again.
4. **Product status:** whether an artifact is a public record, an experiment, a release, or a commercial offering.

The screenshots support a contemporaneous record of the displayed material. They are not, by themselves, an independent audit of every underlying assertion. The appropriate next question is which proposition is being tested and which supporting artifact answers it. A stable governance contract can be evaluated separately from changing model capability.

## Provenance and preservation

`IMAGE_MANIFEST.csv` maps each public filename to its supplied source filename, input SHA-256, published SHA-256, byte counts, operation, subject, and description. The six supplied screenshots were republished under stable, business-readable names. Two remain byte-identical; three larger JPEGs were normalized for publication with standard JPEG encoding and metadata stripping so the repository remains portable. No crop, text, or semantic content was changed, and the operation column records the distinction.

A SHA-256 digest establishes exact file identity for the bytes that were published. It does not establish that a displayed count, interpretation, or model-capability statement is factually correct. Reviewers should cite the repository path, commit, screenshot context, and any supporting public artifact together.

The 8 September screenshot collection contains the six supplied screenshots. The 9 September entry above links to the separately published replay evidence. Private audit dossiers, credentials, and unpublished evidence are outside the scope of this repository.

## Related public records

- [Deterministic replay certificate registry](https://github.com/Grounded-DI/grounded-di-replay-certificate-registry)
- [Grounded DI desktop builds](https://github.com/Grounded-DI/GroundedDI-Desktop-Builds)
- [Deterministic Intelligence 2026](https://github.com/Grounded-DI/Deterministic-Intelligence-2026-)

## Public discovery tags

#GroundedDI #DeterministicIntelligence #DeterministicAI #AuditableAI #ReplayableAI #AIProvenance #AIGovernance #AIEngineering
