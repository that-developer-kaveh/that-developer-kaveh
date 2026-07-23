## Kaveh Alemi

Co-founder of **[latchkey](https://latchkey.dev)** — GitHub Actions that fix themselves.
Cloud Solution Architect at Microsoft. Previously AWS, across 50+ engagements with
Canadian government and enterprise.

`vancouver, bc` · [`kaveha.com`](https://kaveha.com)

---

### why I care about your CI

I spent three years inside other people's pipelines — mostly regulated ones, where a
misconfigured workflow is an incident report, not a slow build. The same three things
were wrong almost everywhere:

- **cache that never hits** — runners paying full price to rebuild what didn't change
- **matrix jobs re-running unchanged work** — minutes billed for zero information
- **third-party actions pinned to a mutable tag** — a supply-chain hole with a friendly name

latchkey is what I built about it: an agentic backend that finds these in your Actions,
then opens the PR that fixes them.

### open source

Published by **[latchkey](https://github.com/latchkey-dev)** — my co-founder writes most
of this code; I bring the pipelines it learned from.

- **[CI-Doctor](https://github.com/latchkey-dev/CI-Doctor)** — an agent skill that teaches
  your AI to diagnose and durably fix failing pipelines. MIT.
- **[cache-action](https://github.com/latchkey-dev/cache-action)** ·
  **[docker-cache-action](https://github.com/latchkey-dev/docker-cache-action)** —
  streaming cache and ECR layer caching.
- **[runner-benchmarks](https://github.com/latchkey-dev/runner-benchmarks)** — the numbers, published.

Mine:

- **[personal-website](https://github.com/kaveh-personal-sites/personal-website)** —
  [kaveha.com](https://kaveha.com). Astro, zero JS shipped by default, deploys itself on push.

### on the quiet contribution graph

Most of what I've built is someone else's production and stays there. Landing zones,
compliance guardrails, and Kubernetes for governments and banks don't come with a public
repo. If you want that detail it's on [kaveha.com](https://kaveha.com) — and if you'd
rather just watch me work, point me at a slow workflow.

---

`11x aws certified` · `4x azure certified` · `aws security sme` · `mscs georgia tech` · `1 patent`

[kaveha.com](https://kaveha.com) · [linkedin](https://www.linkedin.com/in/kvalemi/)
