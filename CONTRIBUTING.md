# Contributing

Thank you for contributing to Human-First Writing Skill.

## Contribution Philosophy

The project exists to improve writing quality.

Good contributions should make writing:

* clearer
* more natural
* more specific
* more context-aware
* more accurate
* more useful
* better at preserving the author's voice

---

## Good Contributions

Examples include:

* identifying repetitive AI-style patterns
* improving vocabulary guidance
* adding useful writing styles
* improving platform-specific rules
* adding localization guidance
* improving voice preservation
* improving factual safeguards
* adding realistic examples
* improving evaluation tests

---

## Avoid

Do not contribute rules that intentionally:

* add spelling mistakes
* add grammatical errors
* create artificial awkwardness
* insert random slang
* manipulate punctuation solely to imitate humans
* manipulate statistical writing patterns solely for detector evasion
* fabricate personal experiences
* fabricate evidence
* fabricate citations

---

## Adding a New Style

Add a file under:

```text
styles/
```

For example:

```text
styles/storytelling.md
```

Include:

1. Purpose
2. Characteristics
3. Preferred language
4. Common mistakes
5. Examples where useful

---

## Adding a New Platform

Add a file under:

```text
platforms/
```

Describe:

* audience
* typical format
* tone
* length considerations
* platform-specific conventions

---

## Changing Core Behavior

If a change affects general writing behavior:

1. Update the appropriate file under `rules/`.
2. Check whether `SKILL.md` needs an update.
3. Update examples.
4. Update evaluation prompts.
5. Update `CHANGELOG.md`.

---

## Pull Requests

Explain:

1. What changed?
2. Why was the change necessary?
3. Which behavior does it improve?
4. Which files were changed?
5. Were examples or tests updated?

---

## Quality Standard

A contribution should make the system better for actual readers.

The standard is not:

> "Can this fool a detector?"

The standard is:

> "Does this produce better writing?"
