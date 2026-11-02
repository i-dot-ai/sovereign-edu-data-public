---
title: What a tool has to do
nav_order: 8
---

# What a tool has to do

{: .in-short }
The twelve things a tutoring tool needs to do to take part, in plain words.
Everything else about how a tool works is up to the tool.

## Naming the pupil

1. **Use the school's ID for the pupil.** Each pupil has one ID per school, given by the school's own system.

## Sessions

{: start="2"}
2. **Create an ID for each session**, and put it on every record from that session.
3. **Close each session** with a "completed" record, so we know it's over.

## The records to send

{: start="4"}
4. **Send three kinds of record:**
   - one for each answer, as the session runs,
   - one for the session, naming its unit if the tool knows it,
   - one report at the end, on what the pupil understood and any misconceptions.
5. **Say what each answer was about**: which material it came from, and its unit and lesson if the tool knows them. If it doesn't, the integration layer works them out later.
6. **Record mistakes on answers, not misconceptions.** Why a pupil went wrong goes in the end-of-session report.
7. **Say which version of the curriculum map** each record was written against.

## The actions allowed

{: start="8"}
8. **Use only three actions** in answer records: attempted, answered and completed.

## Timestamps

{: start="9"}
9. **Put a time on every record**, saying when the thing it records happened.

## Sending through the integration layer

{: start="10"}
10. **Send records through the integration layer**, not straight to a store.
11. **Name the tool, and give each record an ID**, so we know who wrote it and a record sent twice is only stored once.
12. **Follow the record format.** Records that fail the checks aren't stored.

## What could change

We could convert a tool's own records ourselves, so tools don't have to change how they record.
That would make it easier to take part, but we'd have to keep a converter for each tool.
