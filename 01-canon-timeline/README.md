# Canon Timeline

A chronological, sourced list of events that happened in-canon. This is the
"what happened, in order" reference — for the raw source text those events
are drawn from, see [`02-transcripts/`](../02-transcripts).

## Rules for this folder

- Every event needs a **Source** (see [PROJECT_RULES.md](../PROJECT_RULES.md)).
- One event per entry. Don't bundle multiple unrelated events into one file
  just because they happened the same day.
- If the exact date is unknown, use the **Chronological position** field
  instead of guessing a date (e.g. "After EV-0004, before EV-0006").
- Every claim in an event file must carry a tag from
  [`../CERTAINTY-LEVELS.md`](../CERTAINTY-LEVELS.md) —
  `[CANON FACT]`, `[STRONG INFERENCE]`, or `[MY INTERPRETATION]`.
  `[FIC ADDITION]` does not belong in this folder at all; a fictional take
  on an event belongs in `07-story-outlines/` or `08-prose-drafts/`,
  linked from "Related entries" instead.
- Speculative connections between events ("this probably caused that") get
  tagged `[MY INTERPRETATION]` inline, and/or get a fuller writeup in
  [`06-interpretations-theories/`](../06-interpretations-theories) linked
  from "Unresolved questions" or "Related entries" — never stated as bare
  fact.

## Suggested organization

Once there's enough content, consider either:
- One file per event (`YYYY-MM-DD-short-event-name.md`), plus an
  `INDEX.md` that lists them in order, or
- A small number of arc/era files, each containing multiple dated entries.

Pick whichever makes sense once real events start getting added — no need
to decide that structure now.

## Template

Copy [`_template-event.md`](_template-event.md) for each new event.
