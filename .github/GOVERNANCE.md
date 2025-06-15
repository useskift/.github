# Governance at Skift

This document centralizes how Skift projects are governed: who makes day-to-day and strategic decisions, how we escalate and document bigger changes, where to report problems (including security), expectations around licensing, and how often governance is reviewed.

## Roles & responsibilities

- **Core maintainers** — Define strategy, handle escalations, and make final calls when consensus can't be reached.
- **Project maintainers** — Handle day-to-day operations, review and approve contributions per project rules, and escalate governance items when required.
- **Community moderators** — Keep community interactions aligned with our code of conduct and forward governance or conduct reports to the right people.

> [!TIP]
> If it's unclear who owns a decision, first consult the repository `README` and `CODEOWNERS`; if that doesn't resolve it, contact a core maintainer.

## Decision making

1. **Consensus** — We favour consensus through transparent discussion (issues, discussions, or RFCs).
2. **RFCs** — Big changes to governance, APIs, releases, or licensing should be proposed as an RFC describing the problem, options, trade-offs, and a recommended solution.
3. **Escalation** — If consensus stalls, core maintainers will decide and record the outcome (linking PRs/issues/RFCs) and notify the project.

## Reporting: what, how, and where

### 📍 Where to report

- [GitHub Issues](https://github.com/useskift/.github/issues/new/choose) — for reproducible bugs, repository-specific governance questions, or process issues.
- [GitHub Discussions](https://github.com/orgs/useskift/discussions) — for broader governance conversations and early-stage proposals that aren’t yet RFCs.
- Email — for confidential or sensitive matters that shouldn't be public:
  - [community@skift.work](mailto:community@skift.work) — general governance or community questions
  - [legal@skift.work](mailto:legal@skift.work) — licensing, CLA, or other legal inquiries

### 📝 What to include

- A concise summary of the concern or request.
- Relevant context (repository, links to PRs/issues, dates, and affected versions).
- Any suggested remediation or preferred outcome.

### 🔁 How we handle reports

- Project maintainers or community moderators will acknowledge reports within 3 business days.
- Confidential email reports will be triaged by core maintainers and appropriate stakeholders.
- Where possible, outcomes and next steps will be recorded publicly (issue/PR/RFC) to keep the process transparent.

## Security and incident reporting

Security incidents should be reported only through our [SECURITY.md](SECURITY.md) process. Avoid publishing exploit details publicly. Reports following the security policy will be triaged by maintainers and our security contacts under a coordinated disclosure process.

## Legal, licensing & contributor agreements

- Public projects should include a license file. If a CLA is required, follow the repository’s stated process and route legal questions to [legal@skift.work](mailto:legal@skift.work).
- Observe third-party license obligations and disclose any restrictive dependencies when proposing major architecture changes.

## Access control & protected branches

- Main branches are protected. Merges require at least one maintainer approval and passing CI unless core maintainers grant an exception.
- Access to private repositories or elevated permissions is granted on a need-to-work basis and reviewed periodically.

## Privacy & compliance

We follow privacy-by-design principles and relevant data protection regulations (e.g., GDPR/CCPA) where applicable. Projects that collect or process personal data must document the data flows and controls and consult legal when needed.

## Changes to this document

Updates to this document should be proposed via RFC or a tracked PR. Significant changes must be announced to the wider organisation and linked from the accepting PR.

---

_If you're unsure where to report an issue or what to include, email [community@skift.work](mailto:community@skift.work) and we'll guide it for you._
