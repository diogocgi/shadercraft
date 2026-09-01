# Issue tracker templates

These files are authored here but belong to the **public issue tracker**,
[diogocgi/shadercraft](https://github.com/diogocgi/shadercraft). Copy the whole
`.github/` directory to that repository's root — GitHub reads them from there
and builds the "New issue" chooser out of them.

This file is deliberately **not** called `README.md`: GitHub picks the repo's
front-page README as `.github/README.md` → `README.md` → `docs/README.md`, so a
README here would shadow the public one at the repository root.

| File                             | What it does                                                            |
| -------------------------------- | ----------------------------------------------------------------------- |
| `ISSUE_TEMPLATE/config.yml`      | Turns off blank issues; adds the Discussions / Security / site links     |
| `ISSUE_TEMPLATE/bug_report.yml`  | Bug form — rendering and performance reports go through it too           |
| `ISSUE_TEMPLATE/feature_request.yml` | Feature, tool and format requests                                   |
| `ISSUE_TEMPLATE/question.yml`    | Question form, for when Discussions are not the right fit                |
| `SECURITY.md`                    | Backs the "do not open an issue" security row, and the Security tab      |

Two settings on the tracker repo make the chooser complete:

- **Settings → General → Features → Discussions** — otherwise the Discussions
  contact link 404s; drop that entry from `config.yml` if you keep it off.
- **Settings → Code security → Private vulnerability reporting** — gives the
  Security tab the *Report a vulnerability* button that `SECURITY.md` points at.

The forms label their `Where in the app` dropdown with the user-facing mode
names from `src/state/layouts/modeLabels.ts` — `canvas` is "Workspace" and
`image` is "Photo" there, so the dropdown says the same. When a mode is added,
renamed, or removed, update the three forms to match.
