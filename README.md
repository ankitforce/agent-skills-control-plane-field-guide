# Agent Skills Control Plane Field Guide

Reusable Agent Skills need a control plane before they receive meaningful authority. This companion turns the article’s operating pattern into a review receipt, approval checklist, and revocation runbook.

Canonical article: `TBD - publish the Substack article first, then replace this value with its public URL.`

## Start here

1. Read [the approval checklist](checklists/skill-approval-checklist.md).
2. Copy [the review receipt template](templates/skill-review-receipt.example.json).
3. Validate it against [the schema](schemas/skill-review-receipt.schema.json).
4. Read [agent instructions](AGENTS.md) before an agent modifies a receipt.

## What this is

- A narrow governance starter for imported or internally shared agent skills.
- A way to keep package provenance separate from runtime permissions.
- A review artifact, not a substitute for threat modeling or production change control.

## What this deliberately excludes

- A registry or reputation score.
- Automatic trust decisions.
- Credentials, customer data, or production secrets.
- A claim that a package format alone makes execution safe.
