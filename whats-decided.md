---
title: What's decided
nav_order: 10
---

# What's decided

{: .in-short }
The design choices we've made so far, and why.
All of them are still proposals, open to change if the comments show we've got something wrong.

| Decision | Why |
| --- | --- |
| **Each pupil has one ID per school**, given by the school's own system. | It's enough to join up a pupil's records across tools, without passing a national pupil number around. |
| **There are five kinds of record**: each answer, a readable version of each answer, one record per session, the tool's end-of-session report, and a running summary. | Keeping facts apart from judgements means a judgement can be redone without changing the facts. |
| **Misconceptions are judged at the end of a session**, not on each answer. | One wrong answer rarely shows why it was wrong. |
| **Answers go in a standard learning record store**, and everything else in a store of our own. | A standard store means a real one could replace ours later; the other records don't fit its format well. |
| **Records are never edited.** A correction is added as a new version. | Anything built from a record can always say what it was built from. |
| **A session's topic is a curriculum unit**, such as "Fractions". | That's how a pupil would describe what they learned. |
| **A pupil's summary is updated only when a new report has arrived.** | Updating it uses an AI model, so it's slow and costs money. |
| **The integration layer offers six functions** for tools to call. | One call gets everything for the start of a session; the others are there when a tool needs one thing. |
| **Tools send their records through the integration layer.** | Every record can be checked before it's stored. |
| **Materials come with their description.** | A tool can see what each material covers without opening it. |
| **Unlabelled materials are matched to a lesson later**, in the background. | No tool or teacher has to wait, and earlier records gain their lesson once the match is made. |
