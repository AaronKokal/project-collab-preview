---
title: Project Structure (Routing Map)
description: 
date: 2025-09-15T15:24:18Z
draft: false
tags: [Structure]
categories: [ProjectDocs]
---

How to use this document
- Purpose: define where things live and why; keep directories semantically unique.
- Sections: Directory Intents, Routing Rules, Aliases/Synonyms.
- Rule updates must accompany tree changes in the same PR.

Directory Intents
- `/app/` — 
- `/lib/` — 
- `/ui/` — 
- `/infra/` — 
- `/docs/` — Project and framework docs.

Routing Rules
- MUST place cross‑feature pure helpers in `/lib/`.
- MUST mirror source path for tests with `.test.*` suffix.
- MUST NOT add new top‑level dirs without updating this file.

Aliases and Synonyms
- “helpers”, “utilities” → `/lib/`
- “views”, “pages” → `/ui/`

Deep Dives Index (optional)
- If detailed guides exist, list links here for navigation.

Subsystem READMEs (optional)
- For complex sections, add local `README.md` files (e.g., `src/module_x/README.md`) to explain internals and decisions. Keep these aligned with this Structure and the Mission.
