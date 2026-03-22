---
name: release-notes
description: Write polished release notes from a list of changes with user-facing framing, what changed, and why it matters.
triggers: ["write release notes", "release notes for", "changelog for release"]
---

# Release Notes

## What this skill does
Transforms a raw list of changes (commits, tickets, or a changelog dump) into polished, user-facing release notes. Focuses on what changed and why it matters to the user — not internal implementation details. Adapts tone to match the audience (end users, developers, or enterprise customers).

## How to invoke
/release-notes [version number or release name, list of changes]

## Workflow steps

### Step 1 — Categorize changes
Group changes into standard release note categories: **New Features**, **Improvements**, **Bug Fixes**, **Deprecations**, and **Breaking Changes**. Discard internal-only changes (refactors, test updates, CI changes) unless they affect observable behavior.

### Step 2 — Reframe for users
Rewrite each change from the user's perspective. Replace implementation language ("refactored the auth module") with benefit language ("Sign-in is now 40% faster"). For bug fixes, describe what was broken and what the experience is like now. For breaking changes, clearly state what will stop working and what users must do.

### Step 3 — Write the release header
Produce a short (2–3 sentence) summary paragraph for the release that highlights the most significant changes and the overall theme of the release (e.g., "performance quarter", "enterprise readiness"). Include the version number and release date.

### Step 4 — Format and finalize
Assemble the full release notes document with the header, categorized changes, and any migration notes for breaking changes. Offer a short version (one-liner per change) and a detailed version (with context) if the audience or channel requires different lengths.

## Example outputs
A formatted release notes document with a narrative header, categorized bullet points written in plain language, and a migration guide section if breaking changes are present. Suitable for a changelog page, email announcement, or in-app notification.
