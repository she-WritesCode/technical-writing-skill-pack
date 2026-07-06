# Technical Writing Skill Pack

GitHub-ready repository containing:

- an AI agent skill for drafting technical documentation with explicit human verification gates
- reusable reference packs for gathering inputs, shaping drafts, and reviewing output

## Contents

```text
LICENSE
PUBLISHING.md
skills/
  api-doc-hitl/
    SKILL.md
    agents/openai.yaml
    references/
reference-packs/
  api-doc-reference-pack/
```

## What the current skill does

The included `api-doc-hitl` skill is designed for API documentation work such as:

- API overviews
- endpoint or resource docs
- quick reference guides
- release notes
- migration notes

The workflow is intentionally not one-shot. It emphasizes:

1. source collection
2. source ranking
3. structured drafting
4. explicit uncertainty tracking
5. human verification before finalization
6. stable examples, direct openings, and controlled terminology
7. placeholder sweeps, dry runs, and deprecation-aware review
8. early outcome framing, anti-minimizing language, and snippet clarity
9. whole-doc review for ordering, discoverability, version clarity, and screenshot freshness

## What the reference pack does

The reference pack provides reusable drafting support:

- `source-inventory-template.md`
- `intake-question-bank.md`
- `doc-templates.md`
- `drafting-patterns.md`
- `verification-checklist.md`

Use the pack to prepare better inputs before invoking the skill.

## Suggested usage

1. Fill out the source inventory.
2. Use the intake questions to close gaps.
3. Pick a document template.
4. Invoke the skill to draft from the prepared inputs.
5. Run the verification checklist and a human review pass.

## Installation

If you are using Codex, copy `skills/api-doc-hitl` into your skills directory, typically:

- `~/.codex/skills/api-doc-hitl`

Or keep the repo intact and symlink the skill folder into your local skills directory.

## Publishing

The repo includes:

- `LICENSE`: default MIT license
- `PUBLISHING.md`: short GitHub release checklist

## Notes

- The repo is designed to grow into a broader technical writing toolkit over time.
- The current included skill is still focused on API documentation drafting and review.
- It is not a general landing-page or frontend design skill.
- The reference pack can be used independently of the skill.
