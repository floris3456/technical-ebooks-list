# Book Record Template

**Template only — not an actual recommendation.**

For each verified book edition, copy the YAML front matter and headings below into a new `books/<author>-<short-title>-<edition>.md` file. Keep one canonical record per edition, grouping distinct ebook formats of that edition together.

## Metadata

```yaml
---
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
---
```

**How to fill it out:** Use an exact subject slug from [TAXONOMY.md](../TAXONOMY.md) for `primary_subject` and different, distinct approved slugs in `additional_subjects`. Identify the format for each ISBN in `isbn_by_format`, e.g. `epub` or `pdf`; different formats and editions can use different ISBNs. Leave unverified identifiers blank. Use `YYYY-MM-DD` for `last_verified`. Valid `status` values: `candidate`, `recommended`, and `retired`.

## Suggested book-record body

```markdown
# Book title — edition

## Why consider it?
What does it teach, and why is it a worthwhile candidate?

## Audience and prerequisites
Who is this for, and what should readers know already?

## Subject fit
Why is the primary subject appropriate? Why were any additional subjects assigned?

## Evaluation
Document strengths, limitations, independent assessments, and any caveats.

## Editions, formats, and access
Distinguish editions. Include legitimate publisher, author, or open-access locations.

## Sources
- [Official source](https://example.com/)
```

Do not add copyrighted ebook binaries or link to unauthorized copies. A `candidate` is not a recommendation; verify the edition, availability, and claims before promotion.
