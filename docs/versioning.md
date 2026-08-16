# Canon versioning policy

Canon snapshots use semantic versions in the form `MAJOR.MINOR.PATCH` and tags in
the form `canon-vMAJOR.MINOR.PATCH`.

- increment **MAJOR** for a retcon or other incompatible change to established
  public story truth;
- increment **MINOR** for additive canon, new published episode records, or a
  compatible deprecation; and
- increment **PATCH** for metadata corrections, typo fixes, and clarifications
  that do not change story truth.

Every release records its Git revision, applicable Codex contract versions, and
included publication records. Released versions are immutable; later corrections
produce a new version rather than moving or rewriting a tag.

## Canon snapshot releases

Publish each canon version as an immutable GitHub Release using the tag
`canon-vMAJOR.MINOR.PATCH`. Its snapshot bundle records the exact Universe
commit and includes reader-safe canon data, included publication IDs, the
applicable Codex contract references, license and notices, and a manifest of
file sizes and SHA-256 digests.

Consumers pin the canon version, immutable tag, exact commit, artifact URI,
media type, byte size, and verified digest. `main`, a version range, or a tag
without the artifact digest is not a reproducible input.

## Release ordering

Platform builds a comic release `R` against an already released canon snapshot
`C(n)`. Canon editors approve the resulting public manifest and may include `R`
in a later snapshot `C(n+1)`. The release manifest records `C(n)` as its input;
it must not claim `C(n+1)` as an input when that snapshot contains `R`.

The complete pinning and provenance policy is defined by the
[Studio dependency strategy](https://github.com/DefinitelySecureStudio/studio/blob/main/dependency-strategy/README.md).
