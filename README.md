\# Human-First Writing Skill



A reusable, model-agnostic writing skill for Claude, Kimi, and other LLMs.



This project is designed to produce writing that feels natural, specific, contextual, readable, and consistent with a real writer's voice.



It focuses on reducing common weaknesses of generic AI-assisted prose, including:



\* formulaic sentence structures

\* unnecessary jargon

\* repetitive vocabulary

\* generic introductions

\* artificial sophistication

\* excessive transitions

\* predictable conclusions

\* corporate buzzwords

\* unnecessary verbosity

\* loss of the author's personal voice



> \*\*Important:\*\* This project does not guarantee that content will evade AI detectors. AI-detection systems are probabilistic and can produce false positives. The objective is authentic, high-quality writing rather than detector manipulation.



\## Repository Structure



```text

human-first-writing-skill/

│

├── SKILL.md

├── AGENTS.md

├── CLAUDE.md

├── README.md

├── CHANGELOG.md

├── CONTRIBUTING.md

├── LICENSE

├── .gitignore

│

├── rules/

│   ├── core.md

│   ├── language.md

│   ├── structure.md

│   ├── voice.md

│   ├── factual-integrity.md

│   └── final-edit.md

│

├── styles/

│   ├── conversational.md

│   ├── professional.md

│   ├── analytical.md

│   ├── opinion.md

│   ├── humorous.md

│   └── nepal-context.md

│

├── platforms/

│   ├── facebook.md

│   ├── linkedin.md

│   ├── instagram.md

│   ├── x.md

│   └── email.md

│

├── workflows/

│   ├── rewrite.md

│   ├── draft.md

│   ├── polish.md

│   └── localization.md

│

├── examples/

│   └── before-after.md

│

└── tests/

&#x20;   ├── README.md

&#x20;   └── evaluation-prompts.md

```



\## Basic Usage



Load `SKILL.md` as the primary instruction.



Then apply the relevant modules depending on the task.



Recommended order:



1\. `SKILL.md`

2\. `rules/core.md`

3\. `rules/language.md`

4\. `rules/structure.md`

5\. relevant style file

6\. relevant platform file

7\. relevant workflow

8\. `rules/final-edit.md`



\### Example



For a Nepal-focused LinkedIn opinion post:



```text

SKILL.md

rules/core.md

rules/language.md

rules/structure.md

styles/opinion.md

styles/nepal-context.md

platforms/linkedin.md

workflows/draft.md

rules/final-edit.md

```



\## Design Philosophy



The central principle is:



> \*\*Write for the reader, not for the algorithm.\*\*



The skill does not intentionally add errors, awkwardness, random slang, or strange sentence patterns to imitate human writing.



Instead, natural writing should come from:



\* understanding the subject

\* understanding the audience

\* preserving the author's voice

\* using specific details

\* choosing appropriate vocabulary

\* varying sentence rhythm naturally

\* avoiding unnecessary structure

\* removing filler

\* maintaining factual integrity



\## What This Skill Is Not



This is not a "make AI invisible" system.



It should never:



\* guarantee that content will pass an AI detector

\* manipulate text solely to defeat detection

\* insert artificial mistakes

\* fabricate personal experiences

\* fabricate statistics

\* fabricate citations

\* deliberately make writing worse to appear human



\## Supported Writing Types



The system can be used for:



\* social media posts

\* LinkedIn posts

\* Facebook posts

\* emails

\* business communication

\* reports

\* articles

\* opinion pieces

\* marketing copy

\* captions

\* professional writing

\* humorous writing

\* analytical writing

\* conversational writing

\* Nepal-focused/localized content



\## Extending the System



New styles and platforms should be added as separate modules rather than making `SKILL.md` unnecessarily large.



For example:



```text

styles/

├── storytelling.md

├── persuasive.md

├── academic.md

└── marketing.md

```



or:



```text

platforms/

├── youtube.md

├── threads.md

└── newsletter.md

```



\## Quality Standard



A successful output should be:



\* natural

\* clear

\* specific

\* purposeful

\* accurate

\* context-aware

\* audience-appropriate

\* consistent with the writer's voice



It should not feel:



\* generic

\* formulaic

\* padded

\* unnecessarily sophisticated

\* corporate

\* repetitive

\* mechanically structured



\## License



MIT License.



