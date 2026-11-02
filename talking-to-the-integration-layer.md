---
title: Talking to the integration layer
nav_order: 7
---

# Talking to the integration layer

{: .in-short }
Tools talk to the integration layer (the system that sits between schools and AI tutoring tools) through six functions, using a standard way for AI tools to call services (MCP).

## The six functions

| Function | What it does |
| --- | --- |
| Get classroom context | Everything a tool needs at the start of a session, in one call. |
| Get records | A pupil's past answers and sessions. |
| Send records | Save new answers, sessions and reports. Each one is checked before it's stored. |
| Get the pupil's summary | Where the pupil is in each unit, and any misconceptions. |
| Get materials | The school's materials for a lesson, each with its description. |
| Get the curriculum position | Where a lesson sits: its unit, what comes before and what comes after. |

## What classroom context contains

- **The curriculum position**: the lesson the class is on, and what's around it.
- **The school's materials** for that lesson.
- **The pupil's summary**: what they understand and what they find hard.
- **Their recent sessions**, from any tool.

## A typical session

1. At the start, the tool gets classroom context.
2. During the session, it sends each answer.
3. At the end, it sends the session record and its report.
4. The pupil's summary is then updated, ready for the next tool.
