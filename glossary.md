---
title: Glossary
nav_order: 14
---

# Glossary

{: .in-short }
What the words in this document mean, in plain terms.

**AI tutoring tool**
: An app that uses AI to teach a pupil one to one, for example by asking questions and explaining ideas.
  We sometimes just say "tool".

**Classroom context**
: What a tool needs to know before a session: where the lesson sits in the curriculum, the teacher's materials for it, and what's already known about the pupil.

**Curriculum graph**
: A map of what pupils are taught: each topic (unit) and lesson, and which ones come before which.
  We use [Oak National Academy](https://www.thenational.academy/)'s curriculum graph, standing in for the reference curriculum being developed for DfE.

**Crosswalk**
: A way of linking two different curriculum maps, so that a record written against one can be understood in the other.

**Grounding**
: Matching a piece of teaching material to the lesson it belongs to on the curriculum graph, with a score for how sure the match is.

**ICP (Information Content Profile)**
: A short description of a piece of teaching material, written by an AI: what it teaches, what a pupil needs to know first, what it leads on to, and how demanding it is.

**Integration layer**
: The system we're designing, which sits between schools and AI tutoring tools.
  It gives tools the classroom context before a session, and keeps what they learned after it.

**LRS (learning record store)**
: A standard kind of database for records of learning, such as each answer a pupil gives.
  It stores them as xAPI records. See [what an LRS is](https://xapi.com/learning-record-store/).

**Mastery profile**
: A running summary of how well a pupil understands one topic, built from the reports of every tool they've used.

**Mastery report**
: A tool's judgement, at the end of a session, of what the pupil understood.

**MCP (Model Context Protocol)**
: An open standard that lets an AI tool ask another system for information, or send information to it.
  It's how tools talk to the integration layer. See [modelcontextprotocol.io](https://modelcontextprotocol.io).

**MIS (management information system)**
: The school's main system for pupil records, such as its list of pupils.

**Session**
: One sitting of a pupil with a tutoring tool, on one unit, from when it starts to when it ends.
  Each session has one session record and, at the end, one mastery report.

**SOLO**
: A scale for how well a pupil has understood something, from not yet grasping it to being able to use it in new situations.
  Mastery reports use it. See [the SOLO taxonomy](https://en.wikipedia.org/wiki/Structure_of_observed_learning_outcome).

**Unit**
: A topic in the curriculum, made up of several lessons, such as "Fractions".

**xAPI**
: An international standard for recording learning, used for answer records.
  Each record reads like a sentence: who did what, for example "pupil answered question 3".
  See the [xAPI overview](https://xapi.com/overview/) and the [specification](https://github.com/adlnet/xAPI-Spec).
