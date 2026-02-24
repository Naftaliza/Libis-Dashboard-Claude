CLAUDE.md — Frontend Website Rules
Always Do First
Invoke the frontend-design skill before writing any frontend code, every session, no exceptions.

Reference Images
If a reference image is provided: match layout, spacing, typography, and color exactly. Swap in placeholder content (images via https://placehold.co/, generic copy). Do not improve or add to the design.

If no reference image: design from scratch with high craft (see guardrails below).

Screenshot your output, compare against reference, fix mismatches, re-screenshot. Do at least 2 comparison rounds. Stop only when no visible differences remain or user says so.

Local Server
Always serve on localhost — never screenshot a file:/// URL.

Start the dev server: node serve.mjs (serves the project root at http://localhost:3000).

