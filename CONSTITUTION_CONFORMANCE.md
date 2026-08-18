# Constitution conformance record

## Constitutional alignment

- Constitution: [Definitely Secure Studio Constitution v1.0.0](https://github.com/DefinitelySecureStudio/studio/tree/constitution/v1.0.0)
- Constitution tag: `constitution/v1.0.0`
- Constitution commit: [`a9cc8a503aa30e17820edc62ac95f7cbe10e0564`](https://github.com/DefinitelySecureStudio/studio/commit/a9cc8a503aa30e17820edc62ac95f7cbe10e0564)
- Status: `Conforming` (effective only after accountable-owner approval and merge of the adopting pull request)
- Assessed scope: all reader-safe scaffold files at the assessed revision, including Canon authority, content states, continuity/change policy, Lore promotion boundary, publication templates, versioning, provenance, and repository controls
- Excluded scope: future Canon records, creative assets, snapshots, comics, and releases; no active Canon-bearing or published artifact exists at this revision
- Accountable owner: [`@andrewperis`](https://github.com/andrewperis), Canon editor
- Assessment revision and date: `bcf1827bbe2941204bd7c8d2e60970a523daa840`; 2026-08-17
- Checklist revision: `a9cc8a503aa30e17820edc62ac95f7cbe10e0564`
- Applicable profiles: universal; repository and production-system; creative, Canon, and Lore; release
- Evidence: this record; repository files at the assessed revision; GitHub settings verified 2026-08-17; adoption issue [#3](https://github.com/DefinitelySecureStudio/universe/issues/3); adopting pull request
- Active constitutional exceptions: None
- Residual risk: templates and policy are assessed, but every future Canon decision, snapshot, asset, and publication needs candidate-specific human evidence
- Next review: 2026-11-17, or before the first Canon promotion/publication and on Constitution, Canon authority/state, Lore boundary, rights, audience, release model, owner, visibility, or security change

Before merge this record is proposed and the repository remains `Transition
required`. Owner review and merge are A4 Canon/governance approval and record
the adopting commit. Private Lore and protected evidence stay restricted; this
public repository contains only reader-safe facts and non-derivable attestations.

## Findings

| ID | Severity | Disposition | Evidence |
| --- | --- | --- | --- |
| UN-1 | Major | Resolved in adopting change | Canon-change and comic templates now pin the Constitution and require A4 approval, evidence, effective point, release gates, accessibility, and byte identity. |
| UN-2 | Major | Resolved 2026-08-17 | Secret scanning, push protection, vulnerability alerts, and Dependabot security updates were enabled. |
| UN-3 | Minor | Resolved 2026-08-17 | Undocumented Projects was disabled. |
| UN-4 | Advisory | Deferred by scope | No active Canon or published artifact exists; each future decision/release requires its own review. |

## Checklist evidence

`P` means Pass and `N/A` has the stated rationale. IDs follow the pinned
checklist order.

### Assessment identity

| ID | Result | Evidence or rationale |
| --- | --- | --- |
| I1 | P | Identity, base revision, public audience/environment, scope, and exclusions are exact. |
| I2 | P | Version, immutable tag, full commit, and checklist revision are pinned. |
| I3 | P | `@andrewperis` is accountable Canon editor/CODEOWNER; automation proposes and the human reviews and merges. |
| I4 | P | Profiles, evidence, date, freshness, status, findings, and triggers are recorded. |
| I5 | P | Record is reader-safe; private evidence is represented only by an opaque attestation. |

### Universal profile

| ID | Result | Evidence or rationale |
| --- | --- | --- |
| U1 | P | README, Canon policy, CODEOWNERS, and templates identify authoritative sources and accountable editor. |
| U2 | P | Universe owns public Canon but defers governance/contracts/runtime/private Lore to their authorities. |
| U3 | N/A | No agent or automation runs in this revision. |
| U4 | P | CODEOWNER approval and merge are required A4 Canon/publication actions. |
| U5 | P | Conflicts, uncertain public status, rights, or disclosure stop publication for editor review. |
| U6 | P | Proposed, current, deprecated/superseded, public, and published states are distinct. |
| U7 | P | Universe is reader-safe Canon; Lore is private planning truth and promotion is reviewed. |
| U8 | P | Canon-change records require approval, rationale, effective point, provenance, continuity impact, and preserved history. |
| U9 | P | Lore promotion exports only the smallest approved fact and opaque attestation; private metadata never crosses. |
| U10 | N/A | No generated creative work exists at the assessed revision. |
| U11 | P | Templates require public sources/attestations, contract/source commits, artifact identity, sizes, digests, workflow, and approvals. |
| U12 | P | Public sources and observations remain distinct from private deliberation, omission, and unresolved conflict. |
| U13 | N/A | No nondeterministic generation workflow exists. |
| U14 | N/A | No selected generated output or released bytes exist. |
| U15 | P | Protected Git history, permanent change IDs, immutable snapshots, and release attestations provide ordered evidence. |
| U16 | P | Content boundary, reader safety, rights, private reporting, corrections, and rollback precede publication. |
| U17 | P | Only minimum reader-safe facts/assets and required public metadata are permitted. |
| U18 | P | README, CONTRIBUTING, SECURITY, and templates prohibit secrets and private material in every public surface. |
| U19 | P | Classification follows files, paths, issues, commits, assets, metadata, manifests, and release records. |
| U20 | N/A | No provider processes content in this repository. |
| U21 | P | Assets/contributions require exact provenance, permission, rights, notices, and editor review. |
| U22 | P | Disclosure, provenance, rights, or similarity concerns stop public work and use private escalation. |
| U23 | P | Canon/release criteria cover editorial, continuity, technical, accessibility, safety, rights, provenance, packaging, and publication. |
| U24 | P | Structured validation is bounded; Canon meaning, context, rights, and publication remain human decisions. |
| U25 | P | Stable IDs, authoritative records, portable snapshots, sizes/digests, and immutable history provide durable control. |
| U26 | N/A | No provider-specific feature exists. |
| U27 | P | Canon changes preserve prior meaning/history and require impact, versioning, downstream notice, and correction paths. |

### Repository and production-system profile

| ID | Result | Evidence or rationale |
| --- | --- | --- |
| R1 | P | README, architecture, CODEOWNERS, LICENSE, and NOTICE define public Canon responsibility, owner, boundaries, and proprietary license. |
| R2 | P | Protected `main`, CODEOWNER review, private reporting, and enabled security protections match the standard; no dependencies exist. |
| R3 | P | Consumer inputs use immutable version/tag/commit/artifact/size/digest tuples and forbid private repository dependency. |
| R4 | P | Public content excludes secrets, Lore, unpublished Canon, protected context, masters, and uncleared assets. |
| R5 | P | This file is the required declaration. |

### Creative, Canon, and Lore profile

| ID | Result | Evidence or rationale |
| --- | --- | --- |
| C1 | P | Templates pin public Canon snapshot, source assets/provenance, rights, audience, content state, and opaque private-context attestation. |
| C2 | P | Canon conflicts use published evidence and editor resolution; recency, omission, repetition, or confidence cannot overrule authority. |
| C3 | P | Canon/release review covers voice/meaning, visual/text quality, ambiguity, accessibility, audience impact, and Lore leakage. |
| C4 | P | Promotion/publication scopes only approved facts and preserves alternatives, corrections, deprecations, retcons, and private deliberation in proper boundaries. |

### Release profile

| ID | Result | Evidence or rationale |
| --- | --- | --- |
| L1 | P | Comic template fixes candidate identity, audience, destination, criteria, owners, governing versions, and artifact digests. |
| L2 | P | Template requires every applicable Article 9 gate result. |
| L3 | P | Release disposition requires blocking findings to stop and other findings to have accountable disposition. |
| L4 | P | Editorial, Canon, continuity, media/text, schema, technical, provenance, security/privacy/rights, accessibility/safety, packaging, and A4 review are required. |
| L5 | P | Known limitations, notices, support, monitoring, rollback, withdrawal, and corrections are required. |
| L6 | P | Published bytes must match the approved candidate and immutable provenance. |

### Assessment outcome

| ID | Result | Evidence or rationale |
| --- | --- | --- |
| O1 | P | UN-1 through UN-4 are classified; no unresolved Blocker or Major remains in scope. |
| O2 | P | Effective status is exactly `Conforming`; pre-merge status remains `Transition required`. |
| O3 | P | Approval covers only the base revision and adoption diff. |
| O4 | P | Date and material triggers are explicit. |

## Approval

The owner approves this assessment by reviewing and merging the adopting pull
request. Future Canon and publication records require their own A4 evidence.
