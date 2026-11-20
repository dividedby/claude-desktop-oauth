# claude-desktop-oauth

The home page and privacy policy for Claude Desktop, a personal, single-user connector that lets the developer's own Claude assistant use the developer's own Google account (Drive, Sheets, Docs, Calendar, Gmail) through Google's official APIs. The pages exist so the connector's Google OAuth consent screen has public URLs to point to.

- `index.html`: home page.
- `privacy.html`: privacy policy.

Static HTML with inline CSS and no build step. To preview locally:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Licence

MIT. See [`LICENSE`](./LICENSE).
