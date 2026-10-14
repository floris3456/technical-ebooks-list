# Book Record Template

Template only; exclude this file from book counts. Copy the front matter and body structure into `books/<author>-<title>-<edition>.md`.

```yaml
---
work_id: ""
title: ""
authors: []
edition: ""
publication_year: null
isbn_by_format: {}
primary_subject: ""
additional_subjects: []
concepts: []
languages: []
technologies: []
difficulty: unknown
focus: []
formats: []
access: unknown
official_url: ""
last_verified: null
status: candidate
review_status: pending
reviewed_commit: null
---
```

## Metadata rules

`work_id` is a permanent lowercase kebab-case identifier for the intellectual work, shared across editions, formats, and translations. A filename distinguishes an edition. Counts use distinct work identifiers, never file counts.

Use exactly one approved `primary_subject` from [TAXONOMY.md](../TAXONOMY.md). Additional subjects must be substantial, distinct, and different from the primary. The taxonomy defines difficulty, focus, and status values. Concepts are narrower topics, not duplicate categories.

`isbn_by_format` is optional. Keys such as `pdf` or `epub` must be verified; `ebook-unspecified` may label a publisher's electronic ISBN when the file subtype is not established. Do not invent a format to accommodate an ISBN. Empty `formats` and `access: unknown` do not block recommendation.

`last_verified` is the evidence-check date, in `YYYY-MM-DD` form, not proof that every fact or link will remain current. Each source also needs its own publication/update date when provided, or an explicit unknown. A recent access date does not turn an old review into current-edition evidence.

`status`: `candidate`, `recommended`, or `retired`. `review_status`: `pending` or `passed`. Only a later research run may set `passed`, recording the exact previously published commit it inspected in `reviewed_commit`, and its decision in `research/STATE.md`. Material changes to the recommendation or its evidence reset review to pending. Candidate or retired records never count toward the target, even if previously reviewed.

## Required assessment sections

### Recommendation and audience
State the decision, prerequisites, intended reader, concrete learning value, and inspection limits. Do not imply a full-book reading or executed exercises unless actually performed.

### Contents and subject fit
Use inspected contents or sample text to justify the primary subject and meaningful secondary subjects. A contents page establishes scope, not the correctness of every chapter.

### Why it remains relevant today
Identify the teachings still useful now and cite current evidence. Distinguish durable concepts from outdated products, APIs, examples, and advice. Old books are welcome; historical significance alone is not enough.

### Limitations and alternatives
Explain exclusions from the book's scope, dated material, prerequisites, competing options, and what independent evaluation does and does not establish. Do not transfer reviews of older editions to a new edition without qualification.

### Edition and errata check
Record the edition evaluated, source conflicts, known revisions, and the extent of errata inspection. A missing errata list does not prove correctness. Availability is not a selection criterion and must not delay a qualified recommendation.

### Evidence ledger
At least three substantive inspected documents are needed for a recommendation, collectively covering identity/edition, contents, independent expert assessment or educational adoption, and current relevance. Use short local source identifiers to link each material claim to an exact URL plus section/page locator. Record source dates separately from access dates. Mark uninspected leads as leads, not evidence. Unknown metadata and unavailable purchase links are not rejection reasons; unsupported quality claims remain unresolved.

### Next review
List concrete checks needed in the following run. Candidates must say exactly what evidence is missing. Self-review is not a substitute for subsequent-run review.

## Retaining unselected and removed works

Whenever an evaluated work is not selected, add or update its compact entry in [research/UNSELECTED.md](../research/UNSELECTED.md). Preserve work ID, edition, disposition, concise reasoning, exact supporting evidence and a reconsideration condition. Distinguish **deferred evidence** from a supported **quality rejection** or **retirement**. When deleting a former recommendation or list, retain its work decisions and former commit/path reference first; version control is not a substitute for a discoverable decision list. Promotions mark prior decisions superseded rather than erase them. Never count these retained entries as recommendations.

Do not purchase books, store copyrighted book binaries, or link to unauthorized copies. Preserve rejected claims and decisions in the research log rather than padding the recommendation count.
