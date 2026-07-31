## Purpose

This vault exists to preserve the collective intelligence of Cyberpunk Labs.

It is not a notebook.

It is not a journal.

It is not a dumping ground.

It is the long term memory of the studio.

Every note should make the studio smarter.

Every contribution should increase our ability to create extraordinary experiences.

This studio bible is the philosophy layer. It answers what we value, what we preserve, and what kinds of understanding deserve permanent storage.

The build playbook is the operational layer. It answers how we inspect, implement, verify, and report on work.

If you need the working method, read the Cyberpunk Playbook. If you need the long-lived philosophy, read this note first.

---

# Principle 1

## Knowledge over information

We do not collect information.

We capture understanding.

Information answers:

"What happened?"

Knowledge answers:

"Why does this matter?"

If a note only records facts, it is incomplete.

Every note should explain the underlying principle.

---

# Principle 2

## Timeless over temporary

Temporary information belongs in projects.

Timeless understanding belongs in the knowledge base.

When creating a note, ask:

"Will this still be useful five years from now?"

If yes, it belongs here.

If not, it probably belongs in a project or research note.

---

# Principle 3

## One idea per note

Each note should represent one concept.

Avoid giant documents covering many unrelated topics.

Small notes create stronger connections.

Strong connections create better thinking.

---

# Principle 4

## Original thought first

Never save content simply because someone else said it.

After learning from a book, course, article, or video, rewrite the idea in your own words.

Explain it as if teaching another member of Cyberpunk Labs.

If we cannot explain it ourselves, we do not yet understand it.

---

# Principle 5

## Distill before storing

Research is temporary.

Understanding is permanent.

Do not archive endless videos, articles, or PDFs.

Extract the insight.

Store the insight.

Discard the noise.

---

# Principle 6

## Connect everything

Knowledge gains value through relationships.

Whenever appropriate, connect notes to existing ideas.

A note without connections is rarely complete.

Always ask:

"What does this relate to?"

---

# Principle 7

## Build systems, not collections

The goal is not to accumulate thousands of notes.

The goal is to build a network of reusable knowledge.

Every note should increase the intelligence of the entire system.

---

# Principle 8

## Discover reusable principles

Projects come and go.

Principles remain.

Whenever a project teaches something valuable, extract the lesson into a permanent note.

Projects produce knowledge.

Knowledge survives projects.

---

# Principle 9

## Simplicity wins

Create the fewest folders possible.

Create the fewest tags possible.

Create the fewest rules necessary.

Complex systems eventually collapse under their own weight.

---

# Principle 10

## Every note should answer one question

A reader should immediately understand why the note exists.

If the purpose of the note cannot be stated in one sentence, rewrite it.

---

# Principle 11

## This vault belongs to the future

Every note should be understandable by someone who joins Cyberpunk Labs years from now.

Avoid personal shorthand.

Write clearly.

Assume no prior context.

Leave the studio better than you found it.

---

# Principle 12

## AI is a collaborator, not an authority

AI accelerates discovery.

Humans remain responsible for judgment.

Every AI generated insight should be questioned, tested, refined, and connected to existing knowledge before becoming part of the permanent knowledge base.

---

# Principle 13

## The Standard

Before creating any note, ask:

1. Is this knowledge or just information?
2. Will this still matter years from now?
3. Is this one idea?
4. Did I explain it in my own words?
5. Does it connect to something else?
6. Will this make Cyberpunk Labs better?

If the answer to any of these is no, improve the note before saving it.

> **Every note should help Cyberpunk Labs create more meaningful experiences for people. If it does not serve that mission, it does not belong in this vault.**

---

# Principle 14

## Build as Lego blocks

Every project should be made from reusable pieces with clear seams.

The center should hold the shared engine.

The edges should be thin adapters for the specific product, client, or use case.

If a feature cannot be recombined later, it probably needs to be simplified or split smaller.

---

# Principle 15

## Internationalize from day one, translate later

Every user-facing application must wire English, Spanish, and Portuguese locale slots from the first component. The i18n framework is architecture, not a feature — retrofitting it after launch is pure toil with no upside.

- Wire the framework now (next-intl for Next.js, or the equivalent for the stack)
- Externalize every user-facing string from the first commit
- English ships first; Spanish and Portuguese stubs stay empty
- Translations go live when the UI stabilizes — no code changes, just swap JSON files

Three markets, one codebase, one launch cycle. The marginal cost of doing this right from the start is zero. The cost of retrofitting it later is a scavenger hunt across every component.

---

## What belongs where

- Studio Bible: timeless philosophy, identity, taste, and knowledge standards
- Project notes: temporary context, milestones, architecture, features, and implementation details
- SOPs: repeatable operating procedures with a clear owner and lifecycle
- Build Playbook: inspection, implementation, verification, and completion workflow
