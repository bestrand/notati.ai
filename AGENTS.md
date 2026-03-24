This repo contains a collection of practical notes for AI.

Notes live in notes/{name}/ directories. index.html is the index.

Adding a note:
  1. Create notes/{name}/ with the note content
  2. Add entry to index.html
  3. One PR, both files

Updating a note:
  1. Edit the files in notes/{name}/
  2. Follow the conventions of the existing note

Note style:
  - Terse. No prose where a list works.
  - Choose the format that fits the note, e.g. a skill. These conventions are defaults, not rigid requirements.
  - Start with name and one-line description
  - Write for fast orientation and useful direction, not for completeness
  - Cover the operational essentials needed to use the source correctly and quickly
  - Metadata examples: base or endpoint, auth, format or protocol, pagination, required headers, rate limits, license, attribution
  - Sections for each endpoint or concept
  - Prefer the endpoints, parameters, fields, workflows, limits, and gotchas that matter most in practice
  - Prefer the details that save time or prevent mistakes: odd defaults, strict parameter names, paging traps, required headers, undocumented quirks, broken endpoints
  - Gotchas section at the end for non-obvious things
  - Examples are encouraged. Listed fields or choices are illustrative, not mandatory.
  - Do not mirror the full docs or list everything available. Capture what helps readers choose the right path faster.
  - Do not invent requirements. If something important is undocumented, say so. If something is observed rather than documented, make that clear.
  - Keep notes reusable and general. Do not overfit to one example or one narrow use case.
  - Prefer placeholders in examples when specific real-world values are not important to understanding

Commit messages:
  add: {name}          — new note
  fix: {name}          — correction
  improve: {name}      — enhancement

Do not add build tools, frameworks, or dependencies.
Do not change the serving format. It is plain HTML + markdown.
