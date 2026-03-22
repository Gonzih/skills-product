# @gonzih/skills-product

Claude Code skill suite for product managers and product owners. Four skills, one install.

## Install

```bash
npx @gonzih/skills-product
```

Or install globally:

```bash
npm install -g @gonzih/skills-product
```

Restart Claude Code after installing.

## Skills

### `/prd-writer`
Write a Product Requirements Document from a feature description. Produces a complete PRD with problem statement, target users, user stories, success metrics, scope, and open questions.

```
/prd-writer Add a dark mode toggle to the settings page
```

### `/user-story-generator`
Generate a full sprint's worth of user stories with acceptance criteria from a feature description. Stories are sized, prioritized, and packaged into a suggested sprint plan.

```
/user-story-generator User authentication with SSO support
```

### `/roadmap-builder`
Build a quarterly roadmap from a list of initiatives. Organizes work into themes, applies RICE prioritization, and maps dependencies between initiatives.

```
/roadmap-builder Q2 goals: improve onboarding, launch API v2, reduce churn
```

### `/release-notes`
Write polished release notes from a raw list of changes. Rewrites implementation details into user-facing language, categorizes changes, and adds a narrative header.

```
/release-notes v2.4.0 - fixed login bug, added CSV export, deprecated v1 API
```

## License

MIT
