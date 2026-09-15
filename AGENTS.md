# Agent Instructions

## Scope

These instructions apply to AI agents working inside this repository.

## Primary Instruction

Read `SKILL.md` before modifying or extending the writing system.

`SKILL.md` defines the fundamental behavior.

Other files provide specialized rules.

---

## File Hierarchy

### Core

```text
SKILL.md
rules/
```

### Style

```text
styles/
```

### Platform

```text
platforms/
```

### Workflow

```text
workflows/
```

### Examples and evaluation

```text
examples/
tests/
```

---

## Modification Rules

When changing the writing system:

1. Identify the rule that needs changing.
2. Modify the smallest appropriate file.
3. Avoid duplicating the same rule in multiple files.
4. Update examples when behavior changes.
5. Update tests when behavior changes.
6. Update `CHANGELOG.md`.

---

## Writing Behavior

The agent must:

* prioritize user intent
* preserve meaning
* preserve factual accuracy
* preserve voice
* adapt to audience
* adapt to context
* avoid unnecessary jargon
* avoid repetitive structures
* remove filler
* use natural language

The agent must not:

* fabricate facts
* fabricate experiences
* fabricate sources
* fabricate statistics
* deliberately manipulate writing to defeat AI detectors
* intentionally insert mistakes to appear human

---

## Rule Precedence

Use this order:

```text
User request
    ↓
SKILL.md
    ↓
rules/
    ↓
styles/
    ↓
platforms/
    ↓
workflows/
    ↓
final edit
```

If two rules conflict, follow the higher-priority rule.

---

## Quality Standard

A successful change should improve at least one of:

* naturalness
* clarity
* voice preservation
* factual integrity
* contextual accuracy
* maintainability
* readability

without intentionally introducing deceptive detector-evasion behavior.
