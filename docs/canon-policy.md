# Canon policy

## Sources of public truth

Current public canon consists of approved, non-superseded records on `main` at a
tagged canon release. Published comics are primary evidence; approved public
reference records make that evidence navigable and resolve explicit corrections
or retcons.

A pull request, issue, draft, social discussion, private lore record, or omitted
fact is not public canon.

## Review requirements

Every canon change requires:

1. a reader-safety review confirming every fact is already public or approved;
2. CODEOWNERS approval from a canon editor;
3. links to public sources or an editor attestation that reveals no private
   source metadata;
4. continuity review across affected records and publications;
5. a version classification under `docs/versioning.md`; and
6. consistent structured metadata using released Codex contracts.

## Additions, corrections, deprecations, and retcons

- **Addition:** records a new public fact without changing established truth.
- **Correction:** fixes an error in how a published fact was recorded; it does
  not change the underlying story truth.
- **Deprecation:** stops recommending a public term or classification while
  preserving its historical use.
- **Retcon:** intentionally changes established public story truth.

Corrections, deprecations, and retcons preserve a permanent record under
`canon/changes/`. Do not erase the previous public understanding from history.

## Canon conflicts

When records disagree, do not silently choose one. Open a canon-change proposal,
identify the published evidence, and let a canon editor resolve the conflict.
Until merged, the latest approved record remains authoritative.
