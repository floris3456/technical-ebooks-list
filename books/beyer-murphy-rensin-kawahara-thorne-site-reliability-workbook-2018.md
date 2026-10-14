---
work_id: beyer-murphy-site-reliability-workbook
title: "The Site Reliability Workbook"
authors: ["Betsy Beyer", "Niall Richard Murphy", "David K. Rensin", "Kent Kawahara", "Stephen Thorne"]
edition: "2018 O'Reilly edition"
publication_year: 2018
isbn_by_format: {}
primary_subject: reliability-and-observability
additional_subjects: []
concepts: [service-level-objectives, error-budgets, burn-rate-alerting, incident-response, toil-reduction, on-call, postmortems]
languages: []
technologies: [Prometheus]
difficulty: intermediate
focus: [conceptual, practical]
formats: [web]
access: unknown
official_url: "https://sre.google/workbook/index/"
last_verified: "2026-10-14"
status: recommended
review_status: passed
reviewed_commit: "55a8a4e84730c2843885472e26536526288e9604"
---

# The Site Reliability Workbook — 2018

## Recommendation and audience

**Recommend for operators, backend developers and SRE engineers converting reliability principles into team practices**. Monitoring, HTTP services and incident-management familiarity helps. [Google Research](https://research.google/pubs/the-site-reliability-workbook/) and [O'Reilly's July 2018 listing](https://www.oreilly.com/library/view/the-site-reliability/9781492029496/ch05.html) identify its five **editors** and date. It is a distinct implementation-oriented book from the 2016/2026 editions of *Site Reliability Engineering*. [S1], [S2]

## Original prose inspected and subject fit

In the author's [chapter 2, *Implementing SLOs*](https://sre.google/workbook/implementing-slos/), §§Getting Started, Reliability Targets and What to Measure, service outcomes are translated into measurable SLIs and agreed error-budget decisions; the chapter compares logs, probes and client measurements as imperfect SLI implementations. [Chapter 5, *Alerting on SLOs*](https://sre.google/workbook/alerting-on-slos/) uses **precision, recall, detection and reset time** to reject noisy approaches and motivate multiwindow error-budget/burn-rate alerts with examples in Prometheus syntax. [Chapter 9, *Incident Response*](https://sre.google/workbook/incident-response/) distinguishes mitigating a failure from coordinating incident commanders, operations and communications. These are substantive original texts, not just publisher blurbs, and establish primary **Reliability & Observability**. [S3]–[S5]

## Why it remains relevant today

Current [Cloud Monitoring SLO burn-rate guidance](https://docs.cloud.google.com/stackdriver/docs/solutions/slo-monitoring/alerting-on-budget-burn-rate) and [Prometheus alerting principles](https://prometheus.io/docs/practices/alerting/) continue emphasizing users' experience and useful symptom-driven paging. Independent [System Design Space technical book assessment](https://system-design.space/en/chapter/sre-workbook/) discusses SLO adoption, postmortem/incident roles and Google-scale transferability; [Sefism's September 2026 analysis](https://www.sefism.com/resources/the-site-reliability-workbook/) independently evaluates concrete chapters and flags aging tooling. These reviews are practitioner perspectives, not proof of controlled educational outcomes. [S6]–[S9]

## Limits, alternatives and edition care

Strong as a worked operational *process* reference, with testable alerting criteria and SLO decision-making. **2018** Prometheus examples, chat systems and Google-size responder models need current platform checks and smaller-team adaptation; literal configurations are not a 2026 guarantee. The flagship SRE book covers broader foundations; the workbook is different, not an edition duplicate. No complete reading, executed alerting implementation or exhaustive errata audit was claimed. Web format is descriptive, not a criterion for selection.

## Evidence ledger

**Accessed 2026-10-14; source date is separate from retrieval.**

| ID | Inspected evidence and locator | Source date |
| --- | --- | --- |
| [S1] | [Google Research bibliography](https://research.google/pubs/the-site-reliability-workbook/), editors and purpose | 2018 |
| [S2] | [O'Reilly book listing](https://www.oreilly.com/library/view/the-site-reliability/9781492029496/ch05.html), edition and contents | July 2018 |
| [S3] | [Original Google chapter 2](https://sre.google/workbook/implementing-slos/), SLOs and SLIs | 2018 work, online revision unknown |
| [S4] | [Original chapter 5](https://sre.google/workbook/alerting-on-slos/), precision/recall and alert strategies | 2018 work |
| [S5] | [Original chapter 9](https://sre.google/workbook/incident-response/), coordinating incidents | 2018 work |
| [S6] | [Independent System Design Space critique](https://system-design.space/en/chapter/sre-workbook/), SLO and roles | 2026; exact first publication unknown |
| [S7] | [Independent Sefism critique](https://www.sefism.com/resources/the-site-reliability-workbook/), chapters and caveats | September 2026 |
| [S8] | [Current Google Cloud SLO documentation](https://docs.cloud.google.com/stackdriver/docs/solutions/slo-monitoring/alerting-on-budget-burn-rate), alerting | Live; revision unknown |
| [S9] | [Current Prometheus alerting](https://prometheus.io/docs/practices/alerting/), symptom alerts | Live; revision unknown |

## Subsequent-run independent review — 2026-10-14

**Pass, with implementation caveats; reviewed published commit `55a8a4e84730c2843885472e26536526288e9604`.** Reexamined the original authors' [chapter 2, *Implementing SLOs*](https://sre.google/workbook/implementing-slos/), especially measurement choices and error budgets; [chapter 5, *Alerting on SLOs*](https://sre.google/workbook/alerting-on-slos/), especially precision/recall and multiwindow burn-rate logic; and [chapter 9, *Incident Response*](https://sre.google/workbook/incident-response/), including incident commander, communications, and operations roles. These are substantive operational methods, not merely a contents page. [Current Google Cloud burn-rate guidance](https://docs.cloud.google.com/stackdriver/docs/solutions/slo-monitoring/alerting-on-budget-burn-rate) and [Prometheus alerting practices](https://prometheus.io/docs/practices/alerting/) independently corroborate continued practical importance of alert quality and user-visible symptoms. [System Design Space's detailed practitioner assessment](https://system-design.space/en/chapter/sre-workbook/) discusses both applicability and Google-scale limits; it is not a peer-reviewed comparative outcome study.

**Correction and scope:** A 5xx-only HTTP success criterion in an example is not a universal SLI. The historical Prometheus configurations, responder rosters, and tooling require current environment-specific checks; no 2018 command or configuration was executed. The five credited names are editors of a multi-author volume, not sole authors of every chapter. Do not infer comprehensive errata inspection from a missing or inaccessible errata view. The independent review passes the recommendation's enduring SLO/alerting/incident pedagogy, not every literal example.

## Next review

For final audit, test one multiwindow burn-rate rule with current tool documentation, compare incident-role guidance across team sizes, seek stronger independent studies or critical assessments, and review significant corrections. **Subsequent-run review passed; full catalog audit remains outstanding.**
