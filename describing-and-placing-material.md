---
title: Describing and placing material
nav_order: 5
---

# Describing and placing material

{: .in-short }
An AI writes a short description of any piece of teaching material, so it can be matched to the right lesson on the curriculum map.

## The description

We call it an Information Content Profile (ICP). For a worksheet, slide deck or quiz, it lists:

- what it teaches,
- what a pupil needs to know first,
- what it leads on to,
- how demanding it is.

It doesn't mention any curriculum, so the same description works with any curriculum map.

## Matching it to a lesson

Every lesson on the curriculum map has a description too.

1. Compare the material's description with every lesson's, and keep the ten closest.
2. Let a classifier pick the best of those ten.
3. Only treat the match as certain when the classifier is sure enough.
   If it isn't, but the closest lessons all sit in the same unit, keep the unit only.

This happens in the background, so no teacher or tool has to wait.

## Why describe, not tag

- **Teachers don't have to label anything.** The description is made from the material itself.
- **Descriptions still make sense when the curriculum changes.** A material can be matched again against the new map.
- **Two curriculum maps can be linked** through the materials both of them match.
