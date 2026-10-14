---
work_id: zhang-dive-into-deep-learning
title: "Dive into Deep Learning"
authors: ["Aston Zhang", "Zachary C. Lipton", "Mu Li", "Alexander J. Smola"]
edition: "Cambridge first published 2024; author online v1.0.3"
publication_year: 2024
isbn_by_format: {}
primary_subject: artificial-intelligence-and-machine-learning
additional_subjects: []
concepts: [neural-networks, backpropagation, regression, generalization]
languages: [Python]
technologies: [PyTorch, JAX, TensorFlow]
difficulty: intermediate
focus: [conceptual, practical]
formats: [web]
access: unknown
official_url: "https://d2l.ai/"
last_verified: "2026-10-14"
status: recommended
review_status: passed
reviewed_commit: "154e499e02b872a859e7ee6b641b72365dd245a9"
---

# Dive into Deep Learning — Cambridge 2024 and online companion

## Recommendation and inspected contents

**Recommend to Python-capable learners of neural-network training and its mathematics**, not as a 2026 production LLM deployment guide. Original [author §3.1](https://d2l.ai/chapter_linear-regression/linear-regression.html) derives squared loss, linear regression and the Gaussian likelihood (§§3.1.1–3.1.3). Original [§5.3.3](https://d2l.ai/chapter_multilayer-perceptrons/backprop.html) explains gradient propagation by reverse chain rule and saved intermediate computation. Cambridge's original [contents](https://assets.cambridge.org/97810093/89433/frontmatter/9781009389433_frontmatter.pdf#page=5) confirm substantial regression, classification, MLP and attention coverage. These support the AI/ML subject, not an arbitrary Programming secondary tag.

## Identity, currency and limitations

The Cambridge [copyright page (PDF p.4)](https://assets.cambridge.org/97810093/89433/frontmatter/9781009389433_frontmatter.pdf#page=4) states **first published 2024**, with ISBN 9781009389433 specifically for **paperback** (not an ebook identifier). The [author site](https://d2l.ai/) has documentation **v1.0.3** and cites **2023**; online revision, citation year and printed first-publication date are distinct and no page parity is claimed. Independently, [Cornell Spring 2026 CS4782](https://www.cs.cornell.edu/courses/cs4782/2026sp/) calls it a **primary textbook**, giving section references and PyTorch examples while explicitly **not** following any one text exclusively. Its prerequisites include Python and prior ML foundations. Training mathematics remains relevant; framework APIs and frontier model operations can change. No code execution, whole-book reading, exhaustive errata check or format availability research is claimed.

## Source ledger

Checked **2026-10-14**: [S1 Cambridge 2024 copyright and TOC, PDF pp.4–9](https://assets.cambridge.org/97810093/89433/frontmatter/9781009389433_frontmatter.pdf#page=4); [S2 original online edition v1.0.3](https://d2l.ai/), update date unknown; [S3 original chapter §3.1](https://d2l.ai/chapter_linear-regression/linear-regression.html), revision unknown; [S4 original §5.3](https://d2l.ai/chapter_multilayer-perceptrons/backprop.html), revision unknown; [S5 Cornell Spring 2026 primary-text listing](https://www.cs.cornell.edu/courses/cs4782/2026sp/), page updated date unknown. Independent course adoption is not proof of superior outcomes.

## Subsequent-run independent review — 2026-10-14

**Passed after independently reviewing published commit `154e499e02b872a859e7ee6b641b72365dd245a9`.** Reopened the author original [§3.1.3 Gaussian-likelihood argument](https://d2l.ai/chapter_linear-regression/linear-regression.html), [§5.3.3 computational graph and reverse-chain-rule discussion](https://d2l.ai/chapter_multilayer-perceptrons/backprop.html), and Cambridge's [2024 copyright and contents pages](https://assets.cambridge.org/97810093/89433/frontmatter/9781009389433_frontmatter.pdf#page=4), including visually inspecting the printed table of contents. [Cornell CS4782 Spring 2026](https://www.cs.cornell.edu/courses/cs4782/2026sp/) explicitly identifies D2L as a *primary textbook*, but uses other materials too. Core loss/gradient reasoning remains current; no claim of exact print/online pagination or code equivalence, executed frameworks, or comprehensive errata review. Decision: **pass with edition and API caveats**, not an endorsement of all framework snippets.

## Next review

Passed subsequent review; compare specific 2024 print exercises with online v1.0.3 revisions and test representative PyTorch code against pinned contemporary package versions. Check updated author site releases and substantial errata; never count online revision as a second work. Acquisition status is irrelevant.
