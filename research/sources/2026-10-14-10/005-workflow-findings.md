# Substantive follow-up 005 — accessed 2026-10-14

The same four sites from batch 004 now have inspected technical passages; do not count them twice. Document dates remain unspecified.

- C10-S08 https://www.pulumi.com/docs/iac/guides/testing/ — Unit testing / Property testing / Integration testing: mocked unit tests cannot validate real infrastructure behavior. Mixed layers of testing support IaC quality, not replacement of end-to-end checks.
- C10-S09 https://fluxcd.io/flux/concepts/#reconciliation and #kustomization — desired-state reconciliation and drift correction; manual edits may be reverted. Relevant to modern infrastructure lifecycle coverage beyond simple provisioning scripts.
- C10-S10 https://tekton.dev/docs/pipelines/pipelines/ — Using runAfter, retries and task dependency DAG: ordering is explicit, not merely YAML sequence order. Supports modern applicability of pipeline/dependency reasoning.
- C10-S11 https://www.openpolicyagent.org/docs/terraform — Policy Limitations with Terraform Plans, Prerequisites and steps 3–4: policy can evaluate planned changes, but apply-time unknowns remain. The example explicitly names Terraform 0.12.6 and says current-version compatibility is untested. Therefore a currently reachable official tutorial is NOT automatically current executable guidance.
- Reopened C10-S06 https://infrastructure-as-code.com/book/ at Why I wrote this book. This is a repeat page, not another website.

These findings guide candidate caveats and expose topics for broader research (state reconciliation, test limitations, policy gates). They do not alone establish book pedagogical quality. No tutorial was executed.
