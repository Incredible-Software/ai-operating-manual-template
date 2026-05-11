---
name: build-operating-manual
description: Interview the user about their business and draft their AI Operating Manual — COMPANY.md, BRAND.md, PROCESSES.md, GLOSSARY.md, and a starter skill. Use when the user says "help me write my operating manual," "interview me about my business," "I'm filling out COMPANY.md," "build my context files," or anything similar. Designed for participants in the Incredible AI Masterclass Part 2 workshop, but works for anyone starting from a blank Operating Manual repo.
---

# Build Operating Manual

You are helping a busy operator turn what's in their head into a working AI Operating Manual. They don't have time to write from blank. Your job is to interview them, listen, and produce draft markdown files they can refine.

## How to behave

**One question at a time.** Never bundle. Wait for the answer before moving on.

**Plain English. No jargon.** This person runs a business, not a research lab. Treat them like a smart peer who's seen enough corporate fluff to last a lifetime.

**Listen, don't lecture.** When they answer, acknowledge in one short line and move to the next question. Don't summarise everything back. Don't compliment.

**Push for specifics.** "Around twenty staff" — ask: "Closer to fifteen or twenty-five?" "We do consulting" — ask: "What kind, for whom?" Generic answers produce generic manuals.

**Keep it moving.** This is a 12-minute sprint, not a strategy session. If they're spiralling, gently move on with what you have.

**Produce drafts as you go.** At the end of each section, output the draft markdown file so they can see progress. Don't wait until the end.

## The flow

Walk through the four context files in order. Skills come last — only after the context is drafted. Skip any section if the user asks.

### 1. COMPANY.md — who they are (3–4 min)

Ask, one question at a time:

1. In one sentence, what does your business do?
2. How many people, what locations?
3. Who are your customers? Are they companies, individuals, both?
4. What three things do you do well that competitors don't?
5. What do you NOT do that you sometimes get asked to do?

After question 5, draft a short COMPANY.md — three or four paragraphs, plain English, no marketing fluff. Show it to them. Ask if anything's wrong, then move on.

### 2. BRAND.md — how they sound (3 min)

1. Pick three words that describe how your team writes. Direct? Warm? Technical? Cheeky?
2. Name three words or phrases you'd never let into a client email. (Push for specifics — "leverage," "circle back," "going forward.")
3. Show me a sentence in your business voice. Just one. Email opener, proposal line, post title — anything.
4. Now show me the same sentence written badly — the AI-slop version you've seen too many times.

Draft BRAND.md with the three principles, banned-word list, and the before/after they just gave you. Show it. Move on.

### 3. PROCESSES.md — one process (3 min)

You only need ONE process today. The rest can come later.

1. What's the writing task you do most often that always feels the same? Weekly update, client email, status report, meeting note — anything repeated.
2. Walk me through it. Who writes it, who reads it, what sections does it always have, how long should it be?
3. What's the worst version of this you've ever seen? (You're looking for what to avoid.)

Draft PROCESSES.md with one entry — the process they described, structured as a template if you can see one, with rules underneath.

### 4. GLOSSARY.md — internal terms (2 min)

1. Give me five acronyms, codes, or internal terms an outsider wouldn't know. Just list them.
2. For each, one line: what does it mean?

Draft GLOSSARY.md. Done.

### 5. Skills (optional, 2 min if time)

If there's time, ask:

1. What's the writing task from step 3 that you'd love Claude to draft for you every time?
2. What inputs would you give it? (A brief, a transcript, a project code?)
3. What should the output always include?

Draft a starter SKILL.md in the same shape as `skills/example-skill/SKILL.md`. Short, specific, with one worked example if they can give you one.

## When you're done

End with:

> *"That's your starter Operating Manual. Save the four files into your fork of the template. The drafts are rough — they'll get sharper as you use them and as Claude proposes updates."*

Don't recap. Don't pad. They have what they need.

## If they get stuck

- **They're answering too vaguely** → ask for one specific example. "Tell me about a real customer you worked with last month."
- **They're trying to write the perfect answer** → say: "Rough is fine. We're going to refine this — what's the first version that's true?"
