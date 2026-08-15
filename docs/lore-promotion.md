# Lore-to-canon promotion

Promotion moves a specifically approved fact from private planning into the
public canon record. It is an editorial review, not repository synchronization.

## Required process

1. A lore editor identifies the smallest fact or asset proposed for publication.
2. A canon editor confirms it is safe, timely, internally consistent, and free
   of adjacent unrevealed context.
3. The public pull request states only the approved fact, public continuity
   impact, and a canon-editor attestation.
4. CODEOWNERS review and merge make the fact public canon.
5. Published sources and affected records are updated without linking private
   repository locations.

## Information that must not cross the boundary

- private file paths, issue titles, branch names, commit messages, or access
  details;
- rejected alternatives, future variants, or editorial debate;
- unrevealed relationships, chronology, motives, or consequences adjacent to
  the approved fact; and
- raw private context packages, prompts, communications, or working assets.

The private lore record may note that a fact was promoted and link the resulting
public record. The public repository must remain complete and usable without
access to `lore`.
