# Drafting Patterns

Use these patterns to reduce hallucination and drift.

## Pattern 1: Draft from bounded evidence

For each section:

1. List the supporting sources
2. Extract the facts
3. Draft only those facts
4. Mark gaps with `NEEDS-HUMAN-VERIFY`

## Pattern 2: Separate structure from prose

First ask AI for:

- the outline
- the missing information
- the risk areas

Then ask for prose only after the structure looks right.

## Pattern 3: Prefer factual notes before polished writing

Ask AI to produce:

- a fact sheet
- a terminology sheet
- a risk sheet

Then convert those notes into documentation prose.

## Pattern 4: Make the model show its evidence basis

Ask for working notes such as:

- which source supports each section
- which claims are inferred rather than stated
- which claims require human confirmation

## Pattern 5: Draft small before drafting big

Draft one section at a time when:

- the source material conflicts
- the domain is unfamiliar
- examples are not yet validated
- migration risk exists

## Pattern 6: Treat examples as a separate artifact

Generate examples only after the behavioral description is stable. Validate examples against code, tests, or an SME before folding them into the doc.
