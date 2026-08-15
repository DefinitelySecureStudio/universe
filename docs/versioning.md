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

Cross-repository artifact packaging and exact pinning mechanics will follow
[studio issue #33](https://github.com/DefinitelySecureStudio/studio/issues/33).
Until then, consumers pin both an immutable Git commit and the declared canon
version. `main` is the next release candidate, not a reproducible release input.
