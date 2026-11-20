# claude-desktop-oauth

Two static pages (`index.html`, `privacy.html`) that give the "Claude Desktop" personal Google connector a public home page and privacy policy for Google's OAuth consent screen. Plain HTML with inline CSS; no build step, no package.json, no CI.

## Commands

- Run: `python3 -m http.server 8000`, then open `http://localhost:8000`.
- Test: none (no test suite).
- Lint: none (no linter).

## Gotchas

- `privacy.html` is the privacy policy for the OAuth consent screen. Update its "Last updated" date when it changes.
- Public identity is the handle `dividedby` only: no real name or personal email in the pages, commits or docs.
