# House templates

🟢 Standing record — House templates 0.0.0 - Default issue and pull request templates for BigOdom1984 repositories

This repo holds the default issue forms and the pull request template for all BigOdom1984 repositories.

Any repo that does not carry its own templates uses these. A repo can still add its own files, and its own files win over these defaults.

## What is here

- `ISSUE_TEMPLATE/founder-directive.yml` — the form for a Founder Directive: the task, the reason, the proof required, the acceptance test, and the boundaries.
- `ISSUE_TEMPLATE/work-order.yml` — the form for a work order: one repo, one owner, one clear job, with its acceptance test.
- `ISSUE_TEMPLATE/bug-report.yml` — the form for reporting something broken: what happened, what should have happened, and the proof.
- `ISSUE_TEMPLATE/config.yml` — turns off blank issues, so every new issue starts from a form.
- `PULL_REQUEST_TEMPLATE.md` — the checklist every pull request answers: what changed, what was tested, whether the change log rows were added, and the evidence links.

## Labels

The house label set, used the same way in every working repo:

- `founder-directive` — a directive from the Founder
- `status: queued` — waiting to be picked up
- `status: acknowledged` — the assigned seat has acknowledged it
- `status: blocked` — cannot move forward yet
- `status: verified` — done and independently verified
- `type: build` — build or create something
- `type: audit` — check and verify work
- `type: fix` — fix something broken
- `seat: ai-01` — owned by AI-01 (Onyx, General)
- `seat: ai-02` — owned by AI-02 (ChatGPT, Second)
