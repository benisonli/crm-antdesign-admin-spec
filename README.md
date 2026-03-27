# CRM Ant Design Admin Spec

A reusable skill for classifying, structuring, reviewing, and generating **B2B CRM / admin pages** with **Ant Design-style semantics**.

> **Core idea:** classify the page first, then generate the right admin structure.

---

## Why this skill exists

AI often makes two recurring mistakes when generating admin pages:

1. it turns every page into a dashboard
2. it optimizes for visual novelty instead of structure, density, and implementation realism

`crm-antdesign-admin-spec` exists to fix that.

It gives AI a stable way to:
- identify the correct page type
- choose the correct page skeleton
- stay closer to Ant Design-style admin patterns
- produce better prompts and better implementation-ready output

---

## What this skill helps with

This skill is designed for:
- CRM systems
- SaaS admin interfaces
- operations dashboards
- analytics pages
- customer list pages
- configuration / tool pages
- AI-enhanced admin pages

It helps with:
- page-type taxonomy
- layout and structure decisions
- token guidance
- component mapping
- design constraints
- AI prompt generation
- design review

---

## Best-fit page types

This skill helps separate the most common admin page categories:

### 1. Statistics page
- KPI cards
- charts
- time filters
- org tree / hierarchy panel
- management overview

### 2. AI analytics page
- insights
- risks
- recommendations
- KPI + charts + summary blocks
- action-oriented analysis

### 3. List page
- filters
- actions
- tables
- pagination
- dense operational workflow

### 4. Configuration / tool page
- left functional menu
- right config content
- forms
- uploads
- config tables
- save / submit actions

---

## What makes it different

Most UI guidance starts from styling.

This skill starts from **page-type classification**.

That changes the outcome:
- dashboards stop swallowing list pages
- config pages stop looking like analytics pages
- admin pages stay more realistic to build
- prompts become more stable for downstream tools like UIUXProMax

---

## Example use cases

### Example 1
> Design an AI customer insights page for a CRM system.

The skill should classify it as:
- **AI analytics page**

Then guide structure such as:
- title + subtitle
- scope filters
- KPI insight cards
- segmentation blocks
- trend charts
- detail table
- action recommendations

### Example 2
> Design a customer management page with filters and actions.

The skill should classify it as:
- **List page**

Then guide:
- filter bar
- action bar
- table
- pagination

### Example 3
> Design an AI analysis settings page.

The skill should classify it as:
- **Configuration / tool page**

Then guide:
- left functional menu
- right config panel
- form controls
- upload area
- config table

---

## Repository structure

### `skill/`
The actual skill source.

Contains:
- `SKILL.md`
- `README.md`
- `references/`

### `crm-antdesign-admin-spec.skill`
Packaged skill file.

### `docs/`
Publishing and demo support materials, including:
- publish description
- usage examples
- listing copy
- publish checklist
- demo scenario docs

### `visual-assets/`
Release-ready visual assets:
- `banner.jpg`
- `demo-case-ai-insights.jpg`
- `skill-flow-overview.jpg`

---

## How to use

### Option A — use the source skill
Read or install the files under `skill/`.

### Option B — use the packaged skill
Use:
- `crm-antdesign-admin-spec.skill`

### Option C — use the docs as a design kit
The docs and visual assets can also be used as:
- release material
- GitHub project docs
- prompt references
- design-system explanation materials

---

## Works well with

This skill works especially well before or alongside:
- UIUXProMax
- AI HTML page generation
- Ant Design frontend planning
- design review workflows

Recommended pattern:

```text
crm-antdesign-admin-spec
→ classify page type and structure
→ UIUXProMax or implementation workflow
→ generate page / review page / refine page
```

---

## Not intended for

This is **not** the main skill for:
- landing pages
- marketing websites
- mobile-first app UI
- branding-heavy visual exploration
- highly expressive art-direction tasks

---

## Visual assets

This repository includes visual materials for release/demo use:
- `visual-assets/banner.jpg`
- `visual-assets/demo-case-ai-insights.jpg`
- `visual-assets/skill-flow-overview.jpg`

These help explain:
- the skill positioning
- the classification logic
- the value of page-type-first design guidance

---

## Release status

Current status:
- skill source prepared
- references completed
- examples added
- package generated
- publish docs prepared
- demo visuals prepared

This repository is now in a strong **publish-ready candidate** state.
