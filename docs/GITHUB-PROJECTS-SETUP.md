# GitHub Projects Setup Guide

This guide will help you create GitHub Project boards to visualize and track the Yooz roadmap.

## Why GitHub Projects?

GitHub Projects provide a visual board view (similar to Trello) that helps:
- Visualize progress across milestones
- Track issues in different stages
- See what's in progress, what's next, and what's completed
- Collaborate with the community transparently

## Creating Projects

### Project 1: Q4 2025 - Yooz Notes Beta

1. Go to https://github.com/yooz-eco/yooz-roadmap
2. Click the "Projects" tab
3. Click "New project"
4. Choose "Board" template
5. Name it: **Q4 2025 - Yooz Notes Beta**
6. Description: **Launch Yooz Notes public beta and gather initial user feedback**

**Columns to create:**
- **Backlog** - Items planned but not started
- **In Progress** - Currently being worked on
- **In Review** - Awaiting feedback or testing
- **Done** - Completed tasks

**Link milestone:**
- Go to project settings
- Link to "Q4 2025 - Yooz Notes Public Beta" milestone
- All issues with this milestone will appear in the project

**Add issues:**
- Issue #2: Launch Yooz Notes public beta
- Issue #3: Gather and process initial user feedback
- Issue #4: Build community and communication channels

---

### Project 2: Q1 2026 - Yooz Keyboard Alpha

1. Click "New project" again
2. Choose "Board" template
3. Name it: **Q1 2026 - Yooz Keyboard Alpha**
4. Description: **Design and build the first alpha version of Yooz Keyboard**

**Columns:**
- **Planning** - Architecture and design phase
- **In Progress** - Active development
- **Testing** - Alpha testing
- **Done** - Completed

**Link milestone:**
- Link to "Q1 2026 - Yooz Keyboard Alpha" milestone

**Add issues:**
- Issue #5: Plan Yooz Keyboard architecture and timeline

---

### Project 3: Yooz Roadmap (Overall)

Create a meta-project that tracks all products:

1. Create new project
2. Choose "Board" template
3. Name it: **Yooz Roadmap - All Products**
4. Description: **High-level view of the entire Yooz ecosystem development**

**Columns:**
- **Q4 2025** - Current quarter
- **Q1 2026** - Next quarter
- **Q2 2026** - Following quarter
- **Q3 2026** - Future quarter
- **Completed** - Shipped features

**Add all milestones:**
- This gives a bird's-eye view of the entire roadmap
- Drag issues between quarters as priorities shift

---

## Project Views

GitHub Projects support multiple views:

### Board View (Default)
- Visual kanban-style board
- Drag and drop between columns
- Best for tracking active work

### Table View
Add a table view for:
- Sorting by priority, assignee, or labels
- Bulk editing
- Filtering by product (yooz-notes, yooz-keyboard, etc.)

### Roadmap View
Add a roadmap view for:
- Timeline visualization
- See how milestones align
- Track dependencies

To add views:
1. In your project, click "+ New view"
2. Choose view type
3. Configure filters and grouping

---

## Automation

Set up automations to reduce manual work:

### Auto-add items
1. Project settings → Workflows
2. Enable "Auto-add to project"
3. When issues are created with specific labels, auto-add to project

### Auto-move items
1. Enable "Item closed" workflow
2. Automatically moves completed issues to "Done" column

### Status sync
1. Enable "Pull request merged" workflow
2. Updates linked issues when PRs merge

---

## Best Practices

### Keep it up to date
- Update project boards weekly
- Move issues as they progress
- Close completed issues promptly

### Use labels consistently
- `yooz-notes`, `yooz-keyboard`, `yooz-messenger` for product grouping
- `milestone` for critical milestone-blocking issues
- `community` for community engagement tasks
- `feedback` for user feedback tracking

### Make it public
- All projects should be public for transparency
- Community can see what you're working on
- Builds trust and engagement

### Link PRs to issues
- When code is being developed, link PRs to issues
- Shows progress on implementation
- Automatically closes issues when PRs merge

---

## Project Fields

Consider adding custom fields:

### Priority
- 🔴 High
- 🟡 Medium
- 🟢 Low

### Product
- Yooz Notes
- Yooz Keyboard
- Yooz Messenger
- Infrastructure

### Status
- Planning
- In Progress
- In Review
- Done
- Blocked

To add fields:
1. Project settings → Fields
2. Add custom field
3. Choose type (single select, text, date, etc.)

---

## Example Project Structure

```
Q4 2025 - Yooz Notes Beta
├── Backlog
│   └── [Future improvements based on feedback]
├── In Progress
│   ├── #2 Launch Yooz Notes public beta
│   └── #4 Build community channels
├── In Review
│   └── [Items awaiting review]
└── Done
    └── [Completed tasks]
```

---

## Quick Links

- [Create new project](https://github.com/yooz-eco/yooz-roadmap/projects/new)
- [View milestones](https://github.com/yooz-eco/yooz-roadmap/milestones)
- [View issues](https://github.com/yooz-eco/yooz-roadmap/issues)
- [GitHub Projects documentation](https://docs.github.com/en/issues/planning-and-tracking-with-projects)

---

Once you create the projects, update this document with direct links to each project board!
