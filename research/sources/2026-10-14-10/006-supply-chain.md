# Supply-chain source checks 006 — accessed 2026-10-14

New website keys: slsa.dev, sigstore.dev, reproducible-builds.org, in-toto.io. Each fetched successfully; explicitly limited reads below. Relevant to gaps in older delivery books, not book reviews.

- C10-S12 https://slsa.dev/spec/v1.1/levels — Security levels / Build track inspected. Banner says **v1.2 is current**, v1.1 retired. Do not label v1.1 current. Follow v1.2 before a present-day standards claim. Source version known; date not supplied.
- C10-S13 https://docs.sigstore.dev/cosign/verifying/verify/ — Keyless verification using OpenID Connect / Important Note inspected. Verification checks an expected identity, issuer and artifact digest; a valid signature alone is not a general guarantee of safe code. Date/version not supplied; no commands executed.
- C10-S14 https://reproducible-builds.org/docs/definition/ — fetched successfully; concise definition page queued for targeted body read because batch output only exposed metadata. Not yet treated as substantive evidence.
- C10-S15 https://in-toto.io/ — fetched successfully; project introduction queued for body read. Not yet treated as substantive evidence.

Implication to test: delivery automation books should not be sold as complete contemporary software-supply-chain security manuals. Preserve separate security/reliability/deployment distinctions rather than adding unsupported categories.
