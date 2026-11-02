---
title: What we've tested
nav_order: 9
---

# What we've tested

{: .in-short }
Our experiments so far show that describing and matching material works often enough to be useful, but not yet well enough to trust without checks.
All of them used Oak National Academy's own lessons, or versions of them rewritten by an AI.

## Describing material

We asked an AI to describe the same lesson five times.
The five descriptions were always more like each other than like any other lesson's, so a description reliably points to its lesson.
But fewer than half of the ideas listed appeared in all five, so the details vary from one go to the next.

## Matching material to the right lesson

To test this, an AI rewrote each lesson in different words, as a stand-in for a teacher's own version.
We then tried to find the original lesson from the rewrite.

- Picking the closest lesson found the right one about **three times in four**.
- Letting a classifier choose from the ten closest found the right one about **nine times in ten**.
- A description made from a lesson's quiz alone was placed as well as one made from the whole lesson.

## When the curriculum map changes

We changed copies of the map, renaming, splitting, merging and removing lessons, and tried again.

- Renamed and split lessons were still found **nine times in ten**.
- Merged lessons were found only **half** the time.
- Removed lessons weren't noticed by the matching on its own, but a simple check on how close the match was flagged about **four in five** of them.

## Telling easier from harder

An AI wrote an easier and a harder version of each lesson.
The description put the harder version higher about **four times in five**.
We can't be sure yet that this measures difficulty, because the way we wrote the harder versions may have affected the result.

## Linking two curriculum maps

We built a second map by regrouping Oak's units, and matched the same lessons to both.
The matching found which units of the two maps go together, getting **nine in ten** right.
The second map was built from Oak's, so two maps made by different organisations would be harder.

## How much data a year makes

We made full-length practice sessions and measured the records they produced.
For a large group of schools, **storing** a year of records is cheap.
But the proof of concept reads back all of a pupil's past answers at the start of every session, and over a year that adds up to **far more** than what's stored.

## What we haven't tested yet

- The files schools really hold.
- A curriculum map made by another organisation.
- Records from a real tutoring tool.
- Whether any of this makes tutoring better for pupils.
