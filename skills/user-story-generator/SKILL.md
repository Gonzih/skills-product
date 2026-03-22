---
name: user-story-generator
description: Generate a full sprint's worth of user stories with acceptance criteria from a feature description.
triggers: ["generate user stories", "write user stories", "break into stories"]
---

# User Story Generator

## What this skill does
Takes a feature description and produces a prioritized backlog of user stories sized for a sprint, each with a clear title, narrative, and acceptance criteria. Stories follow standard Agile conventions and are scoped to be independently shippable where possible.

## How to invoke
/user-story-generator [feature description]

## Workflow steps

### Step 1 — Decompose the feature
Identify the distinct user-facing capabilities implied by the feature description. Group them by user type or workflow stage. Flag any that are likely epics (too large for a single story) and break them down further.

### Step 2 — Write the stories
For each story, produce:
- **Story ID** — Sequential identifier (e.g., US-01)
- **Title** — Short imperative phrase (e.g., "Filter search results by date range")
- **Narrative** — "As a [persona], I want to [goal] so that [benefit]"
- **Acceptance Criteria** — Bulleted list of testable conditions using Given/When/Then or plain-language checklist format
- **Story Points** — Rough estimate using Fibonacci (1, 2, 3, 5, 8) with a brief rationale
- **Dependencies** — Any other stories or external work this story depends on

### Step 3 — Prioritize and package
Order stories by business value and dependency chain. Group into a suggested sprint plan that fits a standard 2-week sprint (assume ~30–40 points of velocity unless the user specifies otherwise). Highlight the MVP slice — the minimum set of stories that delivers end-to-end value.

## Example outputs
A numbered backlog of 8–15 user stories in a table or structured list, with each story fully specified and a sprint grouping at the end. Output is ready to copy into Jira, Linear, or any sprint planning tool.

## Live Data Sources
- **Intercom JTBD Research Frameworks** (`intercom.com/resources`) — Reference Jobs-to-be-Done interview guides and templates to ensure user stories are grounded in real job triggers, desired outcomes, and hire/fire criteria.
- **Nielsen Norman Group Public Research** (`nngroup.com`) — Draw on published usability research, heuristics, and UX findings to validate personas and acceptance criteria against evidence-based design standards.
