---
name: prd-writer
description: Write a Product Requirements Document with problem statement, user stories, success metrics, scope, and open questions.
triggers: ["write a PRD", "product requirements document", "write requirements for"]
---

# PRD Writer

## What this skill does
Generates a structured Product Requirements Document (PRD) from a feature or product description. Covers the problem being solved, target users, user stories, measurable success metrics, in/out of scope, and open questions that need resolution before work begins.

## How to invoke
/prd-writer [feature or product description]

## Workflow steps

### Step 1 — Gather context
Ask clarifying questions if the description is vague: Who are the target users? What problem does this solve? Are there any known constraints or existing systems involved? If the description is sufficiently detailed, proceed directly.

### Step 2 — Draft the PRD
Produce a document with the following sections:
- **Overview** — One-paragraph summary of the feature and its purpose
- **Problem Statement** — What pain point or opportunity is being addressed, and why it matters now
- **Target Users** — Personas or segments who will use this feature
- **User Stories** — Written as "As a [user], I want to [action] so that [benefit]", covering the primary flows
- **Success Metrics** — Quantifiable outcomes (e.g., conversion rate, error rate, time-on-task) with baseline and target values where possible
- **Scope** — Explicit list of what is in scope and what is explicitly out of scope for this version
- **Open Questions** — Unresolved decisions, dependencies, or assumptions that need answers before development begins

### Step 3 — Review and refine
Invite the user to review the draft. Offer to expand any section, add technical constraints, or adjust the tone for the intended audience (engineering, executive, or external stakeholder).

## Example outputs
A complete PRD markdown document, typically 400–800 words, ready to paste into Notion, Confluence, or a GitHub issue. Sections are clearly headed and the open questions section flags blockers proactively.
