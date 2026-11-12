# Mohammed Huzefa — Architecture Portfolio

A static, expandable architecture portfolio preview. Project content lives in JSON files so new projects can be added without changing the page templates.

## Run locally

From the repository root, run `python -m http.server 8000` and open `http://localhost:8000/`.

## Add a project

1. Add a project entry to `data/projects.json`.
2. Add its detail file under `data/projects/<slug>.json`.
3. Put project images under `images/` and reference paths from the repository root.

Draft descriptions and missing drawings remain marked for review. The pages use `noindex` while the content is being completed.
