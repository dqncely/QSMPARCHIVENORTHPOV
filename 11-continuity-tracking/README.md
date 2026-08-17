# Continuity Tracking

The canonical answer to "who knows what, and since when?" — tracked across
*all* characters in one place, so it doesn't drift out of sync between
individual character sheets. Character sheets
([`03-character-sheets/`](../03-character-sheets)) link into this folder
for their "What this character knows" / "What the audience knows that they
do not" sections rather than maintaining their own separate copy of the
same information.

## Why this exists separately

A revelation usually involves more than one character (who learned it, who
told whom, who's still in the dark, who believes something false instead),
so it doesn't belong to any single character sheet. Keeping it here means
there's exactly one place to update when something changes, instead of N
character sheets that can quietly disagree with each other.

## Folder layout

- [`KNOWLEDGE-INDEX.md`](KNOWLEDGE-INDEX.md) — one-row-per-revelation master
  table for a quick "who knows what" scan. Update this whenever you add or
  change a revelation file.
- One file per revelation/major piece of information, named
  `rev-short-title.md` — copy [`_template-revelation.md`](_template-revelation.md).

## Rules for this folder

- Every revelation gets a stable **Revelation ID** (`REV-0001`, `REV-0002`,
  ...) for cross-linking from character sheets, relationship sheets, and
  timeline events.
- Every claim carries a tag from
  [`../CERTAINTY-LEVELS.md`](../CERTAINTY-LEVELS.md). Who *canonically*
  knows something is usually `[CANON FACT]` or `[STRONG INFERENCE]`; guesses
  about who *might* know but hasn't shown it are `[MY INTERPRETATION]`.
- Link revelations to the [`01-canon-timeline/`](../01-canon-timeline)
  Event ID where they originated and where they were learned/told, so
  knowledge state stays anchored to actual chronology.
- When someone incorrectly believes something else, record it here too —
  false beliefs are part of continuity and matter as much as true ones for
  writing consistent scenes.

## Template

Copy [`_template-revelation.md`](_template-revelation.md) for each new
revelation, and add a row to [`KNOWLEDGE-INDEX.md`](KNOWLEDGE-INDEX.md).
