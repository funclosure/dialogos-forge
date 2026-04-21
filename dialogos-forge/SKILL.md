---
name: dialogos-forge
description: Run a human-AI co-learning loop for philosophy, software, AI, embodiment, or abstract sensemaking using the F.O.R.G.E. protocol. Use when the user wants to explore an idea through dialog rather than get a simple summary, co-read a paper or book, digest long-form media, understand an important figure, build a practical skill path, or maintain a workspace of intake notes, raw notes, forged syntheses, topic state, figure nodes, and durable memory.
---

# Dialogos Forge

## Overview

Use this skill to turn a conversation into a structured co-learning process. Treat the exchange as shared sensemaking, then preserve the work in a filesystem shape that separates raw material, active transformation, current learning state, and durable memory.

## Core stance

Hold two things together:

1. **Dialogos**: generate insight through live tension, not passive summary.
2. **Forge**: move the insight through clear stages so it becomes retrievable and usable.

Use analogies only when they genuinely clarify. Prefer pressure-testing over agreeable paraphrase.

## F.O.R.G.E. workflow

### F — Find

Start from a catalyst:
- article, paper, transcript, code snippet, quote, question, anomaly, or half-formed hunch

Capture the raw artifact before over-cleaning it.

### O — Oppose

Add friction.
- challenge assumptions
- surface contradictions
- compare rival interpretations
- ask what would make the current framing false, shallow, or incomplete

Do not collapse too early into summary.

### R — Refine

Compress the productive tension into a cleaner structure.
Possible outputs:
- one-sentence thesis
- blueprint
- distinction map
- set of principles
- conceptual model

### G — Ground

Translate the refined idea into lived relevance.
Ask:
- How does this change the user's relationship to the world?
- What becomes more visible now?
- What practical or existential difference does this make?

### E — Embody

Turn the insight into an executable form.
Examples:
- code change
- writing prompt
- saved synthesis
- workflow rule
- memory entry
- experiment to run

## Intake modes

Before turning material into a stable topic, identify what kind of incoming object it is.

Supported intake modes:
- `source-digestion`
- `co-reading`
- `skill-acquisition`
- `figure-inquiry`
- `concept-inquiry`
- `embodiment-inquiry`

Read `references/intake-model.md` when you need routing guidance.
Use `references/intake-template.md` when capturing a new incoming object before it becomes a full topic thread.

## Recommended workspace shape

Use this layout when creating or organizing artifacts:

```text
dialogos/
  inbox/
  forge/
  syntheses/
  state/
  figures/
  templates/
memory/
MEMORY.md
```

### Folder roles

- `dialogos/inbox/`: raw captures, excerpts, rough notes, unresolved fragments
- `dialogos/forge/`: active transformations and intermediate outputs
- `dialogos/syntheses/`: strong finished pieces worth revisiting
- `dialogos/state/`: current position in each learning thread
- `dialogos/figures/`: recurring people who become stable nodes across threads
- `dialogos/templates/`: reusable scaffolds
- `memory/`: dated durable notes only when the user wants persistence
- `MEMORY.md`: sparse, high-value long-term truths and decisions

Prefer folders by **function and refinement stage**, not by date alone. Use dates as metadata, not the primary organizing principle.

## Retrieval rules

For best later retrieval, separate the artifact from the learner state.

- The **artifact** stores the content.
- The **state file** stores where the user currently is.
- **Resonance** stores why this matters, including historical resonance, personal resonance, why-now, and the relationship being realized.

Think of the artifact as the map, the state file as the pin, and resonance as the felt relevance that makes the map worth returning to.

When revisiting a topic, read the matching `dialogos/state/<topic>.md` first, then open linked artifacts as needed.

## Artifact template guidance

If the material is still arriving and has not yet become a stable thread, use an intake note first.
If it is already a working artifact, use the standard artifact template.

Intake notes should include historical resonance, personal resonance, why-now, and relevance realization, not just descriptive metadata.

Each artifact should begin with lightweight structure:

```md
# Title

## Type
dialogos-inbox | forge-output | synthesis | memory-candidate

## Date
YYYY-MM-DD

## Themes
theme1, theme2, theme3

## Source
conversation | article | paper | podcast | book | code | other

## Status
raw | in-progress | distilled | embodied

## Body
...
```

Keep it lightweight. Do not turn note-taking into bureaucracy.

## State file guidance

Use one state file per active topic, for example:
- `dialogos/state/grounding.md`
- `dialogos/state/selfhood.md`
- `dialogos/state/agency.md`

Each state file should track:
- current F.O.R.G.E. phase
- current grip or working thesis
- why the thread is alive
- historical resonance
- personal resonance
- why now
- relationship shift
- open questions
- active artifacts
- last meaningful shift
- next move

Read `references/state-template.md` and `references/artifact-template.md` when you need exact scaffolds.

## Movement rules between layers

Move material according to refinement level:

1. **Inbox → Forge** when a raw artifact is being actively pressure-tested.
2. **Forge → Syntheses** when the output becomes coherent, revisitable, and worth keeping.
3. **Any layer → memory/** only when the insight is durable enough to matter beyond the current thread.
4. **memory/ → MEMORY.md** only for especially stable cross-project truths, preferences, or decisions.

Do not promote material just because it is recent. Promote it when it has earned persistence.

## When writing or updating artifacts

1. Name files by concept, not only date.
2. Keep titles semantically rich.
3. Link the current topic state file to the active artifacts.
4. Update the state file whenever the user's learning edge changes.
5. If the thread reaches execution, record the embodiment step explicitly.

## Deliverables this skill commonly produces

- a new artifact in `dialogos/inbox/`
- a forged note in `dialogos/forge/`
- a topic state file in `dialogos/state/`
- a polished synthesis in `dialogos/syntheses/`
- a small durable memory note, if the user wants persistence

## Figure guidance

Use a figure file when a person recurs, anchors multiple ideas, or the user explicitly wants to understand what they represent.

A figure file should track:
- what the person represents
- signature ideas
- core distinctions
- linked threads and artifacts
- related figures
- open questions

Read `references/figure-template.md` when creating or updating a figure node.

## Resources

- `references/intake-model.md`: intake modes and routing logic for incoming learning material
- `references/intake-template.md`: starter template for a new intake note
- `references/artifact-template.md`: starter template for inbox, forge, and synthesis artifacts
- `references/state-template.md`: starter template for tracking where the user currently is in a learning arc
- `references/figure-template.md`: starter template for recurring figure nodes
- `references/movement-rules.md`: concise rules for when material should move between inbox, forge, syntheses, and memory
