---
name: roadmap-builder
description: Build a quarterly roadmap with themes, initiatives, prioritization rationale, and a dependency map.
triggers: ["build a roadmap", "quarterly roadmap", "product roadmap"]
---

# Roadmap Builder

## What this skill does
Constructs a structured quarterly roadmap from a list of initiatives, goals, or feature ideas. Organizes work into themes, applies a prioritization framework, surfaces dependencies between initiatives, and produces a format suitable for sharing with leadership, engineering, or customers.

## How to invoke
/roadmap-builder [list of initiatives, goals, or context about the product and quarter]

## Workflow steps

### Step 1 — Establish context
Identify the planning horizon (default: one quarter), the primary audience for the roadmap (internal team, executives, customers), and any fixed constraints such as hard deadlines, compliance requirements, or team capacity. Ask for clarification if these are not provided.

### Step 2 — Define themes
Group initiatives into 2–4 strategic themes that reflect the product's goals for the quarter (e.g., "Reliability", "Growth", "Developer Experience"). Each theme should have a one-sentence rationale explaining why it matters this quarter.

### Step 3 — Prioritize initiatives
Apply an explicit prioritization framework — default to RICE (Reach, Impact, Confidence, Effort) unless the user specifies another (MoSCoW, Value vs. Effort, etc.). For each initiative, provide:
- **Theme** — Which theme it belongs to
- **Initiative** — Brief name and description
- **Priority** — High / Medium / Low with a one-line rationale
- **Rough size** — S / M / L / XL
- **Quarter placement** — Now / Next / Later, or specific month

### Step 4 — Map dependencies
Identify initiatives that must be completed before others can start. Produce a simple dependency list (e.g., "Initiative B requires Initiative A to be complete") and flag any critical path items that could block the quarter's goals.

## Example outputs
A roadmap document with a theme overview, a prioritized initiative table, and a dependency list. Optionally formatted as a now/next/later grid. Suitable for presenting in a planning meeting or embedding in a strategy doc.
