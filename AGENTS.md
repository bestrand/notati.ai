This repo contains a collection of notes for AI.

Notes are flat markdown files at the repo root. index.md is the index.
sync.yaml tracks source URLs, hashes, and last sync dates per note.

Adding a note:
  1. Create {name}.md at root
  2. Add entry to index.md under the right category path
  3. Add entry to .github/notati.yaml with sources to monitor
  4. One PR, all three files

Updating a note:
  1. Edit {name}.md
  2. Update last_sync in .github/notati.yaml
  3. Update last_hash if content source changed

Note style:
  - Terse. No prose where a list works.
  - Start with name and one-line description
  - Key-value metadata: base, auth, format, pagination
  - Sections for each endpoint or concept
  - Gotchas section at the end for non-obvious things
  - Link related notes with see also at the bottom

Commit messages:
  sync: {name}         — automated sync update
  add: {name}          — new note
  fix: {name}          — correction
  improve: {name}      — enhancement

Do not add build tools, frameworks, or dependencies.
Do not change the serving format. It is plain markdown.
