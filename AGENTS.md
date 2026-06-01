# Agent instructions

## Cursor Cloud specific instructions

This repo is a **single-file static app** (`index.html`, vanilla JS). No `npm install` or build step.

### Run locally

From this directory:

```bash
python3 -m http.server 8082
```

Open http://127.0.0.1:8082/

### Smoke test

1. Click **查看示例报告** to render built-in `DEMO_DATA`.
2. Or use http://127.0.0.1:8082/?paste=1 for the paste-JSON workflow (client-side only).

`#gist:<id>` uses the GitHub API and needs outbound network access.

### Lint / test

None defined in-repo.
