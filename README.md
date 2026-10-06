# Project 3633 — Acceleration of Nonlinear Functions for Edge-AI Processors

Final project, Tel Aviv University. Supervisor: Oren Ganon.

This repository hosts the project website (GitHub Pages). The site has two files:

| File | What it holds | How often it changes |
| --- | --- | --- |
| `index.html` | The page itself and the reference material (concepts, integration, measurement) | Rarely |
| `progress.yml` | Milestones, progress log, reading list, supervisor questions | Every week |

## Publish the site (one time)

1. Create a new repository on GitHub, for example `project-3633`. Make it **Public** (GitHub Pages is free for public repositories).
2. Upload `index.html`, `progress.yml` and this `README.md`: on the repository page choose **Add file → Upload files**, drag them in, and commit.
3. Go to **Settings → Pages**. Under *Build and deployment*, set *Source* to **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
4. After a minute the site is live at `https://<your-username>.github.io/project-3633/`.
5. Open `progress.yml`, replace `YOUR-USERNAME/project-3633` on the `repo:` line with your real username and repository name, and commit. This turns on the "Edit progress on GitHub" link at the bottom of the site.

## Give your partner edit access

**Settings → Collaborators → Add people**, enter your partner's GitHub username. Once they accept, they can edit `progress.yml` too.

Your instructor only needs the site link. No account is needed to view it.

## Update progress

1. Open `progress.yml` on GitHub and click the pencil icon (or use the "Edit progress on GitHub" link at the bottom of the site).
2. Change what you need, for example:
   - a milestone's `status:` to `doing` or `done`
   - a reading's `done:` to `true`
   - a new log entry under `log:`
   - Oren's answer under a question, and `settled: true`
3. Click **Commit changes**. The site updates in about a minute (refresh the page).

Example of a new log entry:

```yaml
log:
  - date: 2026-10-20
    by: Ariel
    text: Met Oren. We build on his RISC core; the board is a Nexys A7.
  - date: 2026-10-06
    ...
```

If the site shows "progress.yml has a formatting error", open the file and check the line it names. The usual causes: a tab instead of spaces, wrong indentation, or text containing `: ` that is not wrapped in double quotes.

## Viewing the site on your own computer

Opening `index.html` directly from a folder will not load `progress.yml` (browsers block it). Either use the GitHub Pages link, or run `python3 -m http.server` in this folder and open `http://localhost:8000`.
