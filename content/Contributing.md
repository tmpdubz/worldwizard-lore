# Contributing to the Lore

This knowledge base grows in two ways: through the World Wizard sessions that established the ages, and through campaigns run in this world. This page explains how to add to it without breaking what's already here.

---

## Two Tiers of Content

### World Canon
The main folders — **Peoples, Geography, Cities, History, Avatars** — are settled, group-approved lore. They represent what is objectively true about the world. 

Editing these files requires group sign-off, except for minor corrections (typos, clarifications that don't change meaning).

### Campaign Content
The **Campaigns** folder is in-progress lore. Each campaign has its own subfolder. Add here freely — no approval needed. This is your scratchpad.

---

## Running a Campaign

1. Create a folder under `Campaigns/` named after your campaign
2. Add an `Overview.md` describing the premise, region, and player characters
3. After each session, add a session log to a `Sessions/` subfolder

**Use an LLM to write session logs.** After the session, give it a rough recap and the relevant lore pages for context. Ask it to write a narrative summary in the style of the existing session notes. The result goes straight into the repo.

Copy the templates in `Campaigns/_Templates/` to get started.

---

## Session Log Format

A good session log has four sections:

**Context** — What the characters knew going in. The region, the stakes, the relevant factions. This is what you'd feed an LLM to prep the next session.

**What Happened** — A narrative recap of the session. Prose is fine; bullet points are fine. Enough detail that someone who wasn't there can follow it.

**World-Affecting Events** — The most important section. A short, explicit list of anything that might matter to the broader world: factions encountered, deals struck, things destroyed, people killed, secrets uncovered. Flag anything that could become a canon proposal.

**Open Threads** — Unresolved things. Loose ends, player hooks, unanswered questions. Useful for your next session and for other DMs who might cross paths with your campaign.

---

## Proposing a Canon Change

When something from your campaign should become permanent world lore, you write a Canon Proposal.

**What counts as a canon change:**
- A city is founded, destroyed, or significantly changed
- A new people, faction, or major NPC becomes historically significant
- A world-affecting event occurs (war, disaster, political shift, death of an avatar)
- Geography changes
- Anything another DM would need to know before setting a campaign in the same region

**What doesn't need sign-off:**
- Adding detail to existing lore that doesn't contradict anything
- Session logs
- Local NPCs and plot threads that stay within your campaign
- Fixing typos or improving prose

### The Process

1. Create a file in `Canon Proposals/` — use the template
2. Share it with the group (Discord, group chat, wherever you talk)
3. Give people a few days to read it and raise concerns
4. If the group agrees: update the relevant world canon files, then delete the proposal
5. If there's disagreement: discuss, revise the proposal, try again

The key question to ask yourself before proposing: **Does this change the world for everyone, not just my campaign?**

---

## Editing World Canon

When you do have approval to edit a main lore file:

- **Add rather than replace** where possible — existing facts are established, build on them
- **Never contradict** established facts without a canon proposal going through the process
- **Flag conflicts** — if you find something inconsistent, add a note at the bottom of the relevant file rather than silently changing it
- **Use [[wiki links]]** to connect new content to existing pages

---

## Using LLMs with This Vault

The markdown structure is designed to be LLM-friendly. When using an LLM to prep a session or flesh out lore:

- Share the relevant pages as context (paste the text, or link to the GitHub repo)
- Share `Contributing.md` too so the LLM understands what's canon vs. in-progress
- Ask it to flag any contradictions with existing lore before writing new content
- If it generates something good, add it — either as a session log or as a canon proposal

Nothing an LLM writes is automatically canon. It goes through the same process as everything else.
