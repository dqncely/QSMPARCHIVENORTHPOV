# Project Rules

These rules exist to keep **what actually happened in canon** cleanly
separated from **what I think, guess, or make up**. Everything else in this
repo follows from that one goal.

## 1. The three tiers of content

1. **Canon** — things that verifiably happened on stream / in an official
   source. Lives in `01-canon-timeline/`, `02-transcripts/`,
   `03-character-sheets/`, `04-relationship-sheets/`,
   `05-worldbuilding-factions/`.
2. **Interpretation** — my reads, theories, headcanon, and speculation about
   canon. Lives in `06-interpretations-theories/`. Never mixed into a canon
   file without a clear label.
3. **Fiction** — original creative writing built on top of canon and/or
   interpretation. Lives in `07-story-outlines/`, `08-prose-drafts/`,
   `09-finished-stories/`. Fiction is allowed to invent freely — that's the
   point — but it must not be confused for canon later.

## 2. No inventing canon

- Nothing goes into a canon folder (tiers listed above under "Canon")
  without a **Source** — the stream/VOD, date, and (ideally) a timestamp
  or quote from a transcript.
- If you're not sure whether something is canon, it goes in
  `06-interpretations-theories/` and gets flagged with the
  `Confidence: unconfirmed` field until it's verified.
- Nothing in this repo should be treated as a finished canon record until
  it's been cross-checked against `02-transcripts/` (the primary source).
- Every individual claim in a canon file — not just the file as a whole —
  carries a tag from [CERTAINTY-LEVELS.md](CERTAINTY-LEVELS.md):
  `[CANON FACT]`, `[STRONG INFERENCE]`, `[MY INTERPRETATION]`, or
  (fiction files only) `[FIC ADDITION]`. Interpretation never gets
  presented as fact just because it sits next to facts in the same file.

## 3. Transcripts are ground truth

- `02-transcripts/` holds raw, as-close-to-verbatim-as-possible text.
  Don't clean up, summarize, or interpret in place — do that in a
  separate file that links back to the transcript.
- Every other canon file (timeline, character sheets, relationship sheets,
  worldbuilding) should be traceable back to a transcript entry via the
  **Source** field.

## 4. Labeling non-canon content

Every file in `06-interpretations-theories/` must open with a short label
block (see that folder's template) stating it is a theory/interpretation,
not fact. The label must travel with the text — don't rely on folder
location alone, since files get copied, quoted, or moved.

## 5. Fiction can contradict canon on purpose

Story outlines, prose drafts, and finished stories may deliberately diverge
from canon (AU, what-if, headcanon fills, etc.). When a piece does this
intentionally, say so in its front matter (see the templates in
`07-story-outlines/` and `08-prose-drafts/`) so future-you doesn't mistake
a plot choice for a canon fact.

## 6. Formatting

- Markdown only, `kebab-case.md` file names.
- Every content file starts with a small front-matter-style block (plain
  Markdown, not YAML, unless you later want YAML front matter for tooling)
  giving at minimum: **Title**, **Status**, and where relevant **Source**
  or **Canon status**.
- Keep one subject per file (one character, one event, one theory, one
  story) so files stay linkable and mergeable.

## 7. Adding new content — checklist

- [ ] Which tier does this belong to: canon, interpretation, or fiction?
- [ ] Did I copy the right `_template.md` for this folder?
- [ ] If canon: is there a **Source** (stream/date/timestamp)?
- [ ] If interpretation: is it labeled as non-canon in the file itself?
- [ ] If fiction that intentionally breaks canon: is that noted in the file?
- [ ] Does the file name follow `kebab-case.md`?
