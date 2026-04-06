# 📋 Marketing Agency PM Playbook

Your plug-and-play project management system for marketing agencies. Tracks tasks, structures communication, automates reporting, and gets new hires up to speed from day one.

Built for humans, not engineers. No coding required.

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Built for](https://img.shields.io/badge/built%20for-marketing%20agencies-blueviolet)
![Tools](https://img.shields.io/badge/tools-GitHub%20%2B%20Notion-blue)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

**Built by [Iana Pugachova](https://www.linkedin.com/in/iana-pugachova/) — Marketing Project Manager**

---

## 📌 Table of Contents

| # | Section | What's Inside |
|---|---|---|
| 1 | [🧠 What Is This?](#-what-is-this) | The 4 PM problems this playbook solves — and how |
| 2 | [📦 What You Get](#-what-you-get) | Every file, template, and automation included |
| 3 | [⚙️ How It Works](#️-how-it-works) | The three layers and which tool does what |
| 4 | [🗓️ Your Daily Flow](#️-your-daily-flow) | Exactly what to do Monday through Friday |
| 5 | [🚀 Quick Start](#-quick-start) | Get your team live in under an hour |
| 6 | [🟢 The Easy Way (Non-Technical)](#-the-easy-way-non-technical) | No-code version — just click this, then that |
| 7 | [🔌 Connecting Your Tools](#-connecting-your-tools) | GitHub ↔ Notion ↔ Slack in minutes |
| 8 | [🎨 Customization](#-customization) | Make it yours — labels, cadence, branding |
| 9 | [👤 Credits](#-credits) | Who built this and why |

---

## 🧠 What Is This?

A ready-to-use project management system built specifically for marketing agencies. It solves the four problems every PM team runs into:

| Problem | What This Fixes |
|---|---|
| Tasks fall through the cracks | A clear system for creating, assigning, and tracking every piece of work |
| Updates get lost in DMs | Communication protocols so nothing is missed |
| Status reports take forever | Templates you fill in — not write from scratch |
| New hires don't know how things work | A step-by-step onboarding guide for day one |

This is **not a software tool**. It's a set of documents, templates, and automations you drop into GitHub and Notion — and your whole team follows from day one.

---

## 📦 What You Get

```
marketing-agency-pm-playbook/
│
├── 📄 README.md                         ← You are here
├── 📄 CONTRIBUTING.md                   ← How to keep the playbook updated
│
├── 📁 .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── task.md                      ← Task creation form
│   │   ├── bug.md                       ← Bug / issue report form
│   │   └── campaign.md                  ← Campaign task form
│   ├── PULL_REQUEST_TEMPLATE.md         ← PR checklist
│   └── workflows/
│       ├── stale-issues.yml             ← Auto-flag inactive tasks
│       ├── weekly-digest.yml            ← Weekly task summary
│       └── auto-label.yml              ← Auto-tag tasks by keyword
│
├── 📁 workflows/
│   ├── task-tracking.md                 ← How tasks are created and managed
│   ├── team-communication.md            ← When and how the team communicates
│   ├── reporting.md                     ← How we report to clients
│   └── onboarding.md                    ← New hire guide
│
├── 📁 templates/
│   ├── weekly-status-report.md          ← Friday client update (fill & send)
│   ├── project-brief.md                 ← New campaign kick-off document
│   ├── meeting-notes.md                 ← Notes format for every meeting
│   └── campaign-checklist.md            ← 5-phase launch checklist
│
├── 📁 automations/
│   ├── github-automations.md            ← GitHub Actions code + setup guide
│   └── notion-automations.md            ← Notion rules, formulas, templates
│
└── 📁 tools/
    └── tool-stack.md                    ← Every tool we use and why
```

**13 documents. 4 workflow guides. 4 templates. 3 GitHub Actions. 2 automation guides.**

---

## ⚙️ How It Works

The system has three layers:

**Workflows** — define how work moves through the team (task creation, communication, reporting, onboarding)

**Templates** — documents you fill in, not write from scratch (briefs, reports, meeting notes, launch checklists)

**Automations** — GitHub Actions that run in the background so nothing falls through the cracks

The tool flow is simple:

```
New task?        → GitHub Issue
Brief or doc?    → Notion page
Quick update?    → Slack #projects
Status report?   → Template → Notion → Email to client
Campaign launch? → Campaign checklist
Blocker?         → Label it "blocked" in GitHub
```

### The Core Rule

> **If it is not in GitHub, it does not exist.**

Every task, comment, decision, and blocker lives in GitHub Issues. Notion holds documentation and briefs. Slack is for conversations only — not task management.

---

## 🗓️ Your Daily Flow

```
Monday (30 min)
→ Open GitHub board
→ Move unfinished tasks to "To Do"
→ Create new issues for this week
→ Assign owners and due dates
→ Post standup in #projects
        ↓
Tuesday – Thursday (5 min/day)
→ Update issue status as you work
→ Comment on issues if blocked
→ Label anything stuck as "blocked"
        ↓
Friday (45 min)
→ Mark completed tasks as "Done"
→ Fill in the Weekly Status Report template
→ Send report to client by 12pm
→ Archive completed tasks in Notion
→ Post end-of-week update in Slack
        ↓
Campaign Launch Day
→ Run through the full Campaign Checklist
→ Every checkbox ticked before anything goes live
→ PM signs off → account lead confirms to client
```

**Monday standup format:**
```
📌 [Your Name] — Monday [Date]
✅ Done last week: [key completions]
🔧 This week: [top 3 priorities]
🚧 Blocked by: [anything? or "nothing"]
```

---

## 🚀 Quick Start

**Prerequisites**
- A GitHub account (free)
- A Notion account (free)
- A Slack workspace

**Step 1 — Copy this repository**
Click the green **Use this template** button at the top of this page (or fork the repo).

**Step 2 — Set up your GitHub Project board**
Go to Projects → New Project → Board layout.
Add columns: `Backlog` → `To Do` → `In Progress` → `In Review` → `Done`

**Step 3 — Create your labels**

| Label | Colour |
|---|---|
| `content` | `#0075ca` blue |
| `design` | `#8957e5` purple |
| `strategy` | `#e4a93c` orange |
| `client-facing` | `#2ea44f` green |
| `urgent` | `#d73a4a` red |
| `blocked` | `#f9d71c` yellow |
| `internal` | `#6e7681` grey |
| `playbook-update` | `#0969da` blue |

**Step 4 — Set up Notion**
Follow the structure in [`automations/notion-automations.md`](./automations/notion-automations.md).

**Step 5 — Invite your team**
Add collaborators in GitHub Settings → run a 30-minute onboarding call → share [`workflows/onboarding.md`](./workflows/onboarding.md).

---

## 🟢 The Easy Way (Non-Technical)

You don't need to understand any of the setup above. Here's all you actually do day-to-day:

**Track tasks in GitHub Issues**
Go to the Issues tab → New Issue → pick a template (Task / Campaign / Bug) → fill in the title, assign it, add a label → Submit. GitHub does the rest.

**Update status as you work**
- Starting a task → drag the card to "In Progress"
- Stuck → add the `blocked` label and leave a comment
- Done → close the issue (it moves to "Done" automatically)

**Send your Friday report**
Open [`templates/weekly-status-report.md`](./templates/weekly-status-report.md) → copy into an email or Notion page → fill in the blanks → send.

**Launch campaigns without forgetting things**
Open [`templates/campaign-checklist.md`](./templates/campaign-checklist.md) → tick every box before anything goes live.

You don't need to touch GitHub Actions or any code. The automations are optional and set up once by whoever manages the repo.

---

## 🔌 Connecting Your Tools

The playbook works without any integrations — GitHub, Notion, and Slack out of the box. But connecting them makes everything faster.

**What you can connect:**

| Tool | What it enables |
|---|---|
| GitHub ↔ Notion | Link issues directly inside Notion pages; sync task data |
| GitHub ↔ Slack | Get issue updates posted automatically to #projects |
| Notion ↔ Slack | Notion automations post directly to a Slack channel |

**How to connect GitHub ↔ Notion**

Option A — Native (free): Notion Settings → Connections → GitHub → Authorise

Option B — Zapier (no-code): New Zap → GitHub (trigger: New Issue) → Notion (action: Create Database Item)

Option C — Make.com (more control, free tier): Same as Zapier with more filtering options

**How to connect GitHub ↔ Slack**

Slack → Apps → GitHub → Install → in any channel type `/github subscribe owner/repo-name`

Recommended: subscribe `#projects` to issue activity, `#general` to releases only.

**How to connect Notion ↔ Slack**

Notion Settings → Connections → Slack → Connect → set automations to post to a channel.

**GitHub Actions (already included)**

| File | What it does | When it runs |
|---|---|---|
| `stale-issues.yml` | Flags issues with no activity after 7 days | Every Monday 9am |
| `weekly-digest.yml` | Posts a summary of all open issues | Every Friday 8am |
| `auto-label.yml` | Adds labels based on keywords in the issue title | When a new issue opens |

These run automatically once the repo is on GitHub. No maintenance needed.

---

## 🎨 Customization

**Labels**
Edit [`workflows/task-tracking.md`](./workflows/task-tracking.md) to match your services. Replace `content` with `copywriting`, `design` with `creative`, or add `paid-media`, `seo`, `influencer`.

**Reporting cadence**
If you report bi-weekly instead of weekly, update the schedule in [`workflows/reporting.md`](./workflows/reporting.md) and the cron in `weekly-digest.yml`.

**Templates**
Copy any file in `templates/` and rename it. Follow the same format. Link it in this README and in [`CONTRIBUTING.md`](./CONTRIBUTING.md).

**Branding**
Add your agency name and logo to the top of this README. Add a brand guide link to `tools/tool-stack.md`. Customise the status report template with your header/footer.

**More issue types**
Add `.md` files to [`.github/ISSUE_TEMPLATE/`](./.github/ISSUE_TEMPLATE/):
- `content-review.md` — for content approval tasks
- `client-request.md` — for ad-hoc client requests
- `retainer-task.md` — for monthly retainer deliverables

---

## 👤 Credits

Built by **Iana Pugachova**, Marketing Project Manager.

Built to solve real problems in real marketing agency workflows — with a focus on clarity, consistency, and cutting out the noise.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Iana%20Pugachova-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iana-pugachova/)

---

> **Have a suggestion?** Open a GitHub Issue with the label `playbook-update`.
> **Found this useful?** Give the repo a ⭐ and share it with your team.

*Last updated: April 2026*
