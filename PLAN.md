# Plan: one public RFC for the whole system

A draft plan for agreeing with Yunus and Sam Howe before we write anything.

## What we're making

One document that explains the whole system, which we'll publish as a website and ask people to comment on.

It's for two kinds of reader:

- **Non-technical readers**, such as DfE, school leaders and teachers, who want to know what it does and why.
- **Technical readers**, such as the Pioneers, other suppliers and engineers, who want to know how it works.

Both read the same document.
It starts simple and gets more detailed as it goes, so people can stop when they've read enough.

## How it will look

- Written in **markdown**, in this repo.
- Published as a website with **GitHub Pages**, updating automatically when we merge a change.
- **Moving diagrams** to show how things flow:
  - Mermaid diagrams for the system and the records, which GitHub Pages can draw.
  - A few short animations (GIF or SVG) of one pupil's journey, taken from the live demo.
- Each section opens with a short **"In short"** box, so a reader can skim.

## How people will comment

The repo is public, so anyone with a GitHub account can take part:

- **Comments under each page**, using giscus, which stores them in the repo's GitHub Discussions.
- **A "Suggest a change" link** on each page, which opens an edit as a pull request.
- **Issues**, for bigger points, with a simple template.

We'll set a **comment window**, for example four weeks, and name who decides.

## The document, section by section

| # | Section | What it covers | Where it comes from |
| --- | --- | --- | --- |
| 1 | **In one page** | The problem, the idea, what we've shown, and what we're asking for | RFC-0012, report #75 |
| 2 | **Why this matters** | Tools that start from scratch with every pupil; teachers' own materials; a pupil's learning lost when they change tool | Problem definition, report #75 "Why it is built this way" |
| 3 | **One pupil's journey** | A story: a new pupil, Tool A, the teacher's quiz, Tool B picking up where Tool A left off | The live demo, the journey notebooks |
| 4 | **How it works: the big picture** | The shared curriculum map, the service in the middle, the school's systems, the tools | RFC-0012, the high-level diagram |
| 5 | **Describing and placing material** | The ICP, and matching a material to a lesson (grounding) | RFC-0001 (kept copy), report #64, ADR-0010, ADR-0011 |
| 6 | **The records** | The five kinds of record: answers, sessions, the tool's end-of-session report, the readable event view, the pupil summary | ADR-0002 to ADR-0007, the record spec |
| 7 | **Talking to the service** | The six functions a tool can call, and what classroom context contains | ADR-0008, ADR-0009 |
| 8 | **What a tool has to do** | The twelve requirements, in plain words | Tool requirements |
| 9 | **What we've tested** | The findings, in plain numbers: placing material, curriculum changes, difficulty, linking two curricula, how much data a year makes | Findings F-0004 to F-0025, AP-0014 |
| 10 | **What's decided** | The decisions so far, and why | RFC-0012's ADRs |
| 11 | **What's still open** | Open questions, and the assumptions rated by risk | Open questions, the assumptions register |
| 12 | **What's next** | The pillars for the next stage | RFC-0014 |
| 13 | **How to comment** | Where and how, and the comment window | - |
| - | **Glossary** | Plain-words definitions, linked from the text | The glossary |

## What stays private

Nothing goes in that we wouldn't want public:

- No details from conversations with the Pioneers (such as the Medly and Pearson papers).
- No internal names, Slack messages, costs or contracts.
- Only synthetic data, which is all we use anyway.
- Security gaps described as open questions, not as weaknesses to exploit.
- No links into the private repo, since readers can't open them.

## Before we publish

- **Sign-off:** agree who approves it before it goes live (Yunus, Sam Howe, DSIT comms?).
- **Licence:** the Open Government Licence (OGL) for the text, and MIT for any code.
- **Accessibility:** readable headings, alt text on every diagram and animation, and plain language throughout.

## Steps

1. **Agree this plan** with Yunus and Sam Howe.
2. **Set up the repo:** README, licence, how to contribute, an issue template, GitHub Pages, Discussions and giscus.
3. **Write the outline** in full: each section's headings and key points.
4. **Write the sections**, starting with "In one page" and "One pupil's journey".
5. **Add the diagrams and animations.**
6. **Test it** on one non-technical reader and one technical reader, and fix what they found unclear.
7. **Get sign-off and publish**, then open the comment window.
8. **Keep track of comments**, reply to them, and update the document.

## Questions to agree

1. Who signs it off before it's published?
2. How long should the comment window be?
3. Who is the decider at the end?
4. Should the Pioneers be told before it goes public?
