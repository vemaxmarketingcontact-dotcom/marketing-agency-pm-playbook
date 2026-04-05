# 🤝 Contributing to This Playbook

This playbook belongs to the whole team. If something is missing, unclear, or out of date — fix it.

---

## 💡 When to Update This Playbook

Update this playbook when:
- A process changes and the docs don't reflect it
- You find a template is missing a key section
- A new tool is added to the stack
- You discover a recurring mistake that a checklist could prevent
- A new automation is set up that the team should know about

---

## 🔧 How to Suggest a Change

### Minor edits (typos, small wording fixes)
1. Edit the file directly on GitHub (click the ✏️ pencil icon)
2. Commit with message: `fix: [describe the change]`

### Process or template changes
1. Create a **GitHub Issue** with label `playbook-update`
2. Describe what needs to change and why
3. Get one other team member to agree
4. Make the change and reference the issue in your commit

### Adding a new section or document
1. Create a **GitHub Issue** first — describe what you want to add
2. Get PM sign-off
3. Create the new file following the format in this repo
4. Update `README.md` to link to it
5. Commit with message: `feat: add [document name]`

---

## 📝 Writing Style Guide

When writing playbook content, follow these rules:

- **Use plain English** — write for someone on their first week
- **Active voice** — "Create a GitHub Issue" not "A GitHub Issue should be created"
- **Specific over vague** — "by Friday 12pm" not "end of week"
- **Use tables** for comparisons, checklists for steps, prose for explanations
- **Add links** — always link to related documents rather than repeating content
- **Emoji for headers** — use sparingly but consistently for visual scanning

---

## 📁 File Naming Conventions

| Type | Format | Example |
|---|---|---|
| Workflow docs | `kebab-case.md` | `task-tracking.md` |
| Templates | `kebab-case.md` | `project-brief.md` |
| Automation guides | `tool-automations.md` | `github-automations.md` |

---

## 🏷️ Commit Message Convention

```
type: short description

Types:
  feat     → new document or section
    fix      → correction to existing content
      update   → updating an existing process or tool
        remove   → removing outdated content
        ```

        Examples:
        - `feat: add client offboarding checklist`
        - `fix: correct Slack channel names`
        - `update: revise weekly report cadence to Thursdays`

        ---

        ## 🔖 Playbook Versioning

        Significant changes (new workflow sections, major process overhauls) should be noted in the commit message and optionally summarised in a GitHub Release.

        ---

        ## 🙋 Questions

        Open a GitHub Issue with the label `question` and tag the PM.
        