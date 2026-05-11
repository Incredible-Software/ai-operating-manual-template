---
name: example-skill
description: REPLACE THIS — a one-sentence description of what this skill does and when Claude should use it. Include trigger phrases the user might say. The clearer the description, the more reliably Claude will pick this skill when it's relevant. Example pattern (from a real skill — replace with yours) — "Draft a weekly client update for an active project. Use when the user says 'draft a weekly update,' 'project update,' 'Friday update,' or mentions a project code plus 'update'."
---

# [Skill Name] — REPLACE THIS

<!-- 
INSTRUCTIONS: This file is a template for a single SKILL.md. Skills are how Claude
performs repeated tasks the way YOUR business does them.

Replace ALL the placeholder content below with content specific to your skill.
The structure (YAML frontmatter, sections) is the format Claude expects.

See the Anka Civil reference repo for two finished example skills:
- weekly-client-update — drafts a structured weekly project update
- (the Anka repo also includes meeting-summary and proposal-section)
Link: https://github.com/Incredible-Software/ai-brain-demo

The easiest way to draft your own skill: run the build-operating-manual skill 
and at the end, ask it to draft a starter SKILL.md for your most-repeated task.
-->

[Replace this opening paragraph with a 1-2 sentence description of what this skill does. Who it's for, when to use it, what the output should be.]

## When to use this skill

[Replace with: a clearer trigger description than what's in the frontmatter. List the specific phrases or scenarios that should activate this skill. Example: "Use this when the user gives you a brief in any format — bullet points, raw notes, a Fireflies transcript — and asks for a [type of output]."]

## What this skill produces

[Replace with: a description of the output. Format, length, sections, tone. Be specific. The clearer this is, the more reliably Claude produces what you want.]

## Inputs you'll need from the user

[Replace with: a list of inputs the user should give for this skill to work. Examples:
- A project code or reference
- The raw notes or brief
- Hours used vs budgeted
- A deadline
- Any specific people, dates, or context
]

## The template

```
[Replace this block with the exact output template. Subject line, structure, sections.
The more concrete the template, the more reliably Claude fills it in correctly.]
```

## Rules

[Replace with: a list of specific rules for this skill. Examples:
- Always include section X
- Never use the word Y
- If input is missing, ask before drafting
- Keep total length under N words
- Sign off with the user's name, not a generic one
]

## Worked example

[Replace with: ONE worked example. Show real-feeling input followed by the ideal output. 
This is the single most powerful section — Claude learns the pattern from this example 
better than from any rules.]

**Input:**
> [Paste an example of what a user would give this skill.]

**Output:**
> [Paste an example of the ideal output for that input.]
