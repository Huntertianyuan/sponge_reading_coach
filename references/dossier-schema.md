# Dossier Schema

Default root:

`/Users/tianyuan/Documents/Codex/reading-notes/sponge-reading-coach`

Use this root as the canonical shared reading archive when it is accessible, including across Codex, Hermes, or other assistants using this skill. Installing the skill does not create a separate archive; the assistant must continue from this root unless the user explicitly chooses a different one.

Use one folder per book inside the shared root. Folder names should be stable and readable, based on title and author when available. Different assistants may read different books, but they should still create those book folders under the same `sponge-reading-coach` root.

Before starting or resuming a book, inspect the shared root for an existing matching book folder, then read that book's `handoff.md` if present. Also inspect `reading-history-index.md` and `cross-book-index.md` when cross-book context may help.

## Per-Book Files

### `handoff.md`

Fixed entry point for future chats or AI systems. Keep it short and current.

Include:

- title, author, format;
- current reading position;
- current purpose or provisional purpose;
- current reading unit if known;
- live questions;
- major cognitive shifts;
- key concepts and shallow mastery states;
- important reader-generated models;
- important digressions;
- active or recent action experiments;
- next entry point.

Refresh after valuable updates. Do not append everything.

### `book-frame.md`

Store the structural scan and initial strategy:

- metadata;
- table-of-contents map;
- preface/introduction signals;
- central concern;
- broad organization;
- bounded preview of likely core claims;
- initial strategy;
- purpose setting or provisional purpose.

### `reader-trace.md`

Store compressed reader trace, not transcripts:

- meaningful questions;
- judgments;
- confusions;
- counterexample signals and what they changed;
- thought reflections;
- provisional names;
- cognitive shifts;
- reader tendency observations or interpretive hypotheses when supported and useful;
- rare emotional or resistance signals when they matter.

Quote the reader only when exact wording marks an important turn.

### `concepts.md`

Track important concepts:

- author usage;
- reader's initial understanding if known;
- revised understanding;
- examples used;
- mastery state;
- natural recall opportunities.

Also track reader-generated models when they become useful:

- provisional name;
- trigger text anchor or discussion moment;
- what problem or tension the model explains;
- boundary cases or counterexamples;
- maturity cue;
- whether it should remain local or become a cross-book model seed.

### `chapters.md`

Despite the filename, use flexible reading units. Store dense closures for chapters, sections, concept clusters, page ranges, or natural stopping points.

Each closure should be short and high-signal:

- unit covered;
- main line;
- key concepts;
- reader questions;
- critical reminder if useful;
- what can remain unresolved for now when reading is dense;
- optional action experiment;
- next hook when useful.

### `digressions.md`

Capture valuable digressions:

- trigger text anchor or reading moment;
- tight, loose, field-level, or personal connection;
- compressed discussion;
- why it matters;
- whether it becomes a theme seed.

### `actions.md`

Track action experiments and voluntary results:

- source idea;
- small experiment or contact experiment;
- relevance;
- status only if reported;
- result and learning if voluntarily provided.

For contact experiments, avoid streaks, scores, or performance tracking. Record only the source insight, the small noticing practice, and any voluntary reflection.

### `final-internalization.md`

Created at whole-book closure or abandonment closure.

For completed nonfiction, include:

- cognitive gains;
- knowledge gains;
- action gains;
- qualitative absorption judgment;
- reread value;
- living questions;
- theme seeds;
- compact handoff-ready summary.

For abandoned books, include:

- last position;
- reason if offered;
- gains so far;
- possible future return value;
- theme seeds or living questions.

For fiction, keep closure lightweight and experience-centered.

## Cross-Book Files

These files belong directly under the shared root and must be updated by any assistant that makes meaningful book-level or cross-book changes. Do not create assistant-specific copies.

### `reading-history-index.md`

Lightweight index of read or discussed materials:

- title and author;
- broad themes;
- reader's core questions;
- key concepts;
- possible links to future readings;
- personal reading motifs when they clearly recur.

### `cross-book-index.md`

Connect concepts, questions, judgments, action experiments, and theme seeds across books. Keep it sparse and useful, not exhaustive.

Also preserve high-value reader-generated models as cross-book model seeds when they recur across contexts, explain a recurring tension, or may illuminate future books. If reader tendency models or interpretive hypotheses are stored here, keep them provisional, evidence-based, and directly useful for coaching.

## Storage Rules

- Do not store long book excerpts.
- Use text anchors: location, keywords, or brief quotes.
- Keep source notes compact: lookup target, reason, source reference, conclusion.
- Keep dossiers AI-first and human-auditable, not polished reader-facing notebooks.
- Maintain silently except at major milestones or when the reader asks.
