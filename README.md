# Definitely Secure Universe

Reader-safe canon and publication records for *Definitely Secure*.

> [!IMPORTANT]
> This repository is public. A merged canon record is safe for readers and may
> be referenced by public products. Hidden continuity and unrevealed story
> material belong in the private `lore` repository, never here.

## Responsibility

`universe` is the authoritative home for approved public creative canon and the
publication record of *Definitely Secure*. Its scope includes:

- public universe-bible chapters and storytelling rules;
- character, location, and recurring-villain canon;
- published comic metadata and release records;
- approved public story-arc information;
- canon change records and versioned snapshots; and
- web-ready creative assets explicitly cleared for public distribution.

Private world-building belongs in `lore`. Stable identifiers, schemas, manifest
formats, and other implementation-neutral contracts belong in
[`codex`](https://github.com/DefinitelySecureStudio/codex). Production software
belongs in [`platform`](https://github.com/DefinitelySecureStudio/platform).
The organization-wide ownership model is defined in the
[`studio` repository architecture](https://github.com/DefinitelySecureStudio/studio/blob/main/ARCHITECTURE.md).

## Repository layout

| Path | Purpose |
| --- | --- |
| [`bible/`](bible/) | Public universe bible and storytelling rules |
| [`characters/`](characters/) | Reader-safe character canon |
| [`locations/`](locations/) | Reader-safe place and setting canon |
| [`villains/`](villains/) | Reader-safe recurring antagonist canon |
| [`canon/`](canon/) | Canon policy records and explicit changes |
| [`comics/`](comics/) | Published comic metadata and release records |
| [`story-arcs/`](story-arcs/) | Approved public arc information |
| [`assets/`](assets/) | Approved public-facing story assets |
| [`docs/`](docs/) | Canon review, versioning, and lore-promotion policy |

## Public canon boundary

Material may enter this repository only when a canon editor confirms that it is
safe to reveal publicly. Do not commit:

- hidden continuity, future twists, unrevealed relationships, or private
  character history;
- internal fictional communications or world-building notes not yet public;
- production prompt instances, private context packages, or editorial planning;
- credentials, personal data, contracts, or confidential real-world material;
- high-resolution masters or editable creative source files; or
- third-party assets without documented public-distribution permission.

Omission is not a canon statement. The absence of a private fact from this public
repository does not make that fact false, and contributors must not infer or
document hidden material from gaps.

## Canon authority

A pull request is a proposal, not canon. A change becomes public canon only when
it is approved by CODEOWNERS and merged into `main`. Each canon-bearing record
identifies its status and provenance; material marked deprecated or superseded
remains historical context but is no longer current truth.

Read [the canon policy](docs/canon-policy.md) and
[versioning policy](docs/versioning.md) before proposing a change. Material from
private lore follows the [lore-promotion policy](docs/lore-promotion.md); the
public change records only the approved fact and an editor attestation, not the
private source path or unrevealed context.

## Comic records

Published episodes use the permanent `DS-NNNN` identifier defined by the Studio
comic identity. Their canonical record includes title, public number,
publication date, status, approved renditions, and exact contract/release
provenance without copying production code or private inputs into this
repository.

## Contributing and security

Read [CONTRIBUTING.md](CONTRIBUTING.md) before proposing a change. Report an
accidental spoiler, private-material disclosure, or security concern through the
private process in [SECURITY.md](SECURITY.md), not a public issue.

## Rights and license status

No repository-wide license has been selected yet. Until the licensing decision
in [studio issue #31](https://github.com/DefinitelySecureStudio/studio/issues/31)
is completed and explicit terms are added, all text, characters, artwork, comic
records, and other creative material remain all rights reserved. Public
visibility does not grant adaptation, merchandising, model-training, or
redistribution rights.

© 2026 Definitely Secure Studio. All rights reserved.
