# LocalThink

LocalThink builds local-first tools and open formats for saving, owning, and building on AI conversations.

## Projects

### LocalThink Format (LTF)

An open standard for saving AI conversations as portable, readable `.ltf.md` files.

LTF documents are plain Markdown files with structured metadata, designed to be easy to read, move, search, back up, publish, and build tools on.

Repository: [localthink-format](https://github.com/localthink-org/localthink-format)

### LTF Builder

A Chrome extension for exporting ChatGPT, Claude, Gemini, and Grok conversations as LocalThink Format files.

LTF Builder runs only after the user clicks Capture, reads the current conversation page locally, and downloads a `.ltf.md` file without sending conversation content to LocalThink or third-party services.

Repository: [localthink-builder](https://github.com/localthink-org/localthink-builder)

Privacy: [localthink.ai/privacy](https://localthink.ai/privacy)

### LocalThink for Mac

A local-first desktop app for searching, organizing, and continuing saved AI conversations on your own Mac.

Available now for macOS (Apple silicon). Your saved conversation library stays on your computer.

Download: [localthink.ai/download](https://localthink.ai/download)

Privacy: [localthink.ai/privacy](https://localthink.ai/privacy)

### gbrain-localthink

A bridge kit connecting [GBrain](https://github.com/garrytan/gbrain) (Postgres-native personal knowledge brain) with agent session logs — and backing both up to your own git repository.

It does three things: converts agent session JSONL into clean LTF markdown (auto-redacting secrets, PII, and inline images), exports GBrain pages to plain markdown, then commits and pushes both to your own backup repo — idempotent, with a pre-push secret gate that blocks the push if anything looks like a credential.

One `git clone` restores everything on a fresh machine.

Repository: [gbrain-localthink](https://github.com/localthink-org/gbrain-localthink)

## Principles

- Local-first by default
- Portable, readable files
- User-owned AI conversations
- User-owned backup (a git repo, not a SaaS export API)
- Open formats over closed memory silos
- Minimal data collection
- Tools that work with ordinary files
- Sanitize-first before anything leaves your machine

## Website

[localthink.org](https://localthink.org)

Product download and privacy live on [localthink.ai](https://localthink.ai):

- [Download LocalThink for Mac](https://localthink.ai/download)
- [Privacy policy](https://localthink.ai/privacy)
