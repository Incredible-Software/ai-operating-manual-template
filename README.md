# AI Operating Manual — Template

> **This is your starting point.** A blank, well-structured AI Operating Manual ready for your business. Fork or download this repo, run the `build-operating-manual` skill, and replace the placeholders with your own content.
>
> **New here? Open [`START-HERE.md`](./START-HERE.md) first.** Three steps to a working manual.
>
> **Want to see a finished example?** Browse the [Anka Civil reference repo](https://github.com/Incredible-Software/ai-brain-demo) — a worked-example Operating Manual for a fictional 40-person NZ engineering consultancy. Look at it. Don't fork it. Use this template instead.

---

## What's in this repo

| File | What it's for |
|---|---|
| `START-HERE.md` | One-page guide. Read this first. |
| `COMPANY.md` | Who you are, what you do, who you serve |
| `BRAND.md` | How you look (logo, colours, fonts) and how you sound |
| `PROCESSES.md` | How you do common things (templates, rules) |
| `GLOSSARY.md` | Internal codes, abbreviations, terminology |
| `skills/build-operating-manual/SKILL.md` | The interview skill — drafts your manual for you |
| `skills/example-skill/SKILL.md` | A placeholder skill showing the SKILL.md format |

## Three ways to use this template

- **Easiest:** Click the green "Code" button → "Download ZIP." No git knowledge needed.
- **Better:** Click "Use this template" → "Create a new repository." Gives you your own copy on GitHub with one click.
- **Advanced:** Clone with `git clone` — for those comfortable with the command line.

## How to use this with AI tools

**Claude (Pro/Team):**
Open Claude. Start a new chat. Attach `skills/build-operating-manual/SKILL.md` via the paperclip icon. Type *"Run the build-operating-manual skill. Interview me about my business."* Claude will interview you and draft each file. Paste the drafts into the matching files in your repo.

For ongoing use: create a Project, upload your filled-in files as knowledge, paste BRAND.md into the system instructions.

**Microsoft Copilot (Copilot Studio agents):**
Create a new declarative agent. Upload your filled-in files as knowledge sources. Paste BRAND.md into the instructions field (8,000 char limit). Save and test.

**ChatGPT (Custom GPTs):**
Create a new GPT. Upload your files in "Knowledge". Paste BRAND.md into "Instructions".

## When to update each file

- **COMPANY.md** — when the firm changes (new office, principals, services)
- **BRAND.md** — when visual identity changes (logo, colours, fonts) or the way you write changes (rare)
- **PROCESSES.md** — when how you do something changes (often after a retro)
- **GLOSSARY.md** — whenever a new code or acronym becomes standard
- **skills/** — when you identify a new repeated task worth documenting

## How this manual stays alive

A manual that goes stale is worse than no manual. Two patterns keep it current:

**1. Point at live sources, don't duplicate.** Where information already lives in a system of record — your project management tool, shared drive, email, CRM — the manual *references* it rather than copies it. When AI tools connect to those sources (via MCP, Copilot connectors, or similar), they follow the pointer and read the live version.

**2. Claude proposes updates; humans approve.** When you notice a gap, tell Claude. With write access to the repo, it opens a pull request adding the change. You review and merge. Git history is the audit log.

The result: the manual stays in sync with how your business actually operates, without becoming someone's full-time job. We cover both patterns in Parts 3 and 4 of the Incredible AI Masterclass.

## What this is not

This is **not** a customer-facing document. It is internal context for AI tools. It does not replace your quality plan, HR handbook, or project management methodology.

## From the Incredible AI Masterclass

This template is part of the Operating Manual Pack delivered in Part 2 of the [Incredible AI Masterclass](https://incredible.so). Each week, your AI does more for you — Context (Part 2) → Skills (Part 3) → Automation (Part 4).
