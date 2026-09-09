---
name: grill-with-docs
description: A relentless interview to sharpen a plan or design, which also creates docs (ADR's and glossary) as we go.
disable-model-invocation: true
---

Load two sibling skills by reading their files directly. Do not use the Skill tool: both are user-only and it will refuse them. Resolve the paths against this skill's base directory.

1. Read `../grill-me/SKILL.md` and follow it: that is the interview.
2. Read `../domain-modeling/SKILL.md` and follow it alongside, so glossary terms and ADRs get written as decisions land.
