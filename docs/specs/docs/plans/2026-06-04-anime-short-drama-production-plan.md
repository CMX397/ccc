# Anime Short Drama Production Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Build a production-ready starter package for the vertical anime short series "社恐合租喜剧", including episode scripts, storyboard templates, character asset briefs, and a 3-episode pilot validation workflow.

**Architecture:** Start from the approved series spec, then convert it into four concrete production layers: repeatable script format, reusable visual asset definitions, pilot episode storyboards, and a lightweight publishing/test loop. Each task produces a standalone artifact that can be handed to an artist, editor, voice actor, or production partner without extra context.

**Tech Stack:** Markdown documents, storyboard tables, asset briefs, short-video production workflow

---

## File Structure

### New files

- `docs/superpowers/scripts/2026-06-04-episode-01-script.md`
  - Episode 1 full script with hook, dialogue, action, subtitle beats, and ending prompt.
- `docs/superpowers/scripts/2026-06-04-episodes-02-03-outlines.md`
  - Episode 2 and 3 detailed outlines using the same structure as Episode 1, but lighter than a final script.
- `docs/superpowers/storyboards/2026-06-04-pilot-storyboard-template.md`
  - Reusable storyboard format for 35-60 second vertical episodes.
- `docs/superpowers/storyboards/2026-06-04-episode-01-storyboard.md`
  - Shot-by-shot pilot storyboard for Episode 1.
- `docs/superpowers/assets/2026-06-04-character-asset-brief.md`
  - Character turnarounds, expressions, poses, and scene asset requirements.
- `docs/superpowers/assets/2026-06-04-production-style-guide.md`
  - Visual, subtitle, sound effect, and edit rhythm rules.
- `docs/superpowers/production/2026-06-04-pilot-test-checklist.md`
  - Production checklist and validation rubric for the first 3 episodes.

### Existing references

- `docs/superpowers/specs/2026-06-04-anime-short-drama-design.md`
  - Approved series design spec. All deliverables must stay consistent with this document.

---

### Task 1: Lock the episode script format

**Files:**
- Create: `docs/superpowers/storyboards/2026-06-04-pilot-storyboard-template.md`
- Create: `docs/superpowers/scripts/2026-06-04-episode-01-script.md`
- Reference: `docs/superpowers/specs/2026-06-04-anime-short-drama-design.md`

- [ ] **Step 1: Create the reusable script and storyboard header**

Write `docs/superpowers/storyboards/2026-06-04-pilot-storyboard-template.md` with this content:

```md
# Pilot Storyboard Template
