# Transcripts

Raw, as-close-to-verbatim-as-possible transcripts of streams, VODs, or other
primary sources. This is the **ground truth** folder — everything else in
`01-canon-timeline/`, `03-character-sheets/`, `04-relationship-sheets/`, and
`05-worldbuilding-factions/` should trace back to something here.

## Rules for this folder

- Keep transcripts raw. Don't summarize, clean up grammar, or interpret in
  place — do that analysis in a different file (timeline entry, character
  sheet, theory) that links back to the relevant part of the transcript.
- Every transcript file needs a **Source** header: streamer/channel, title,
  date, and a link if available.
- Prefer including timestamps for key moments so other files can cite
  `transcript-file.md @ 12:34` precisely.
- If a transcript is partial (e.g. you only transcribed part of a VOD), say
  so explicitly at the top.

## Folder layout

- [`raw/`](raw) — individual transcript files, one per stream/VOD/source.

## Template

Copy [`_template-transcript.md`](_template-transcript.md) into `raw/` for
each new source.
