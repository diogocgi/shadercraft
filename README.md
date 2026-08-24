# ShaderCraft Alpha v0.1.0

<img width="1664" height="887" alt="image" src="https://github.com/user-attachments/assets/c0d7b5f6-3346-433e-a108-e344fcb88d8e" />

Welcome! This repository is the **public issue tracker** for **ShaderCraft** — an
infinite node canvas hosting focused studios for painting, photo development,
vector work, animation, 3D and more!

**The app is available at shadercraft.com** — the only official site.

---

## What to open here

| I want to… | Open |
|---|---|
| Report something broken, wrong, or crashing | **Bug report** |
| Ask for a new feature, tool, or format | **Feature request** |
| Report a rendering / performance problem | **Bug report** (add the perf details below) |
| Ask a question or discuss an idea | **Discussion** (if enabled) or a **Question** issue |
| Report a security vulnerability | **Do not open an issue** — see [Security](#security) |

Before opening anything, please **search existing issues** (including closed ones).
If you find a match, add a like or comment on it instead of
opening a duplicate.

---

## Reporting a bug

A good report is one I can reproduce without asking you follow-up questions.
Please include:

1. **What you did** — the exact steps, in order, from a fresh document if possible.
2. **What you expected** to happen.
3. **What actually happened** — including any error text.
4. **Which mode** you were in: Workspace, Paint, Photo, Vector, Animation,
   Mesh Viewer, Pixel Wall Art, Mesh Paint or Diagram.
5. **Environment**:
   - Browser + version (e.g. Chrome 141, Firefox 145, Safari 18)
   - Operating system + version
   - GPU / graphics card, if you know it
   - App version (shown in the bottom right corner of the editor)
6. **A screenshot, screen recording, or GIF.** For anything visual — a wrong
   color, a misplaced handle, a stroke that doesn't land where the cursor is —
   this is worth more than paragraphs of description.
7. **A `.shc` project file**, if the bug depends on a specific document and you're
   happy to share it. Drag it into the issue to attach it.

### Extra detail that helps a lot

- **Does it reproduce every time**, or only sometimes? Only on large documents?
  Only after a particular action?
- **Performance problems**: what makes it slow (document size, layer count, zoom
  level, brush size, etc)
- **Data loss / autosave issues**: say whether the document had been saved,
  reloaded, or restored, and roughly how large it was. These get top priority.

---

## Requesting a feature

Describe the **problem**, not only the solution. The most useful requests answer:

- **What are you trying to make/achieve?** The real task, in your words.
- **What does it cost you today?** What you currently do instead, and why that is
  slow, imprecise, or not possible.
- **What would "done" look like?** A sketch, a mockup, or a reference to how
  another tool (Photoshop, Illustrator, Lightroom, Affinity, Blender, Figma,
  Krita, After Effects…) handles it — naming the tool and the feature is a big
  shortcut for me.
- **Which mode** it belongs to, if you have a view.

---

## Priorities

Roughly, in order:

1. **Data loss** — anything that loses or corrupts a document.
2. **Crashes and hard blockers** — the app or a studio is unusable.
3. **Correctness** — a tool produces the wrong result.
4. **Performance regressions** — something that used to be fast.
5. **Missing features and polish.**

ShaderCraft is built and maintained by one person, so response time may vary.

---

## Labels

| Label | Meaning |
|---|---|
| `bug` | Confirmed defect |
| `needs-repro` | I can't reproduce it yet — more detail needed |
| `feature` | New capability requested |
| `enhance` | Improvement to something that already exists |
| `perf` | Speed, memory, or responsiveness |
| `rendering` | WebGL / GPU / driver-specific |
| `ux` | Workflow, layout, discoverability |
| `docs` | Documentation |
| `duplicate` | Tracked elsewhere — see the linked issue |
| `wontfix` | Deliberately out of scope (always with a reason) |
| `shipped` | Fixed or implemented in a released build |

---

## Issue lifecycle

1. **Opened** — triaged and labelled, usually within a few days.
2. **Accepted** — reproduced (bugs) or agreed in scope (features).
3. **In progress** — actively being worked on.
4. **Dismissed** — closed without work: out of scope, already covered by another
   issue, or working as intended. The reason is always written out.
5. **Shipped** — released; the issue is closed with the version it landed in.

An issue tagged `needs-repro` and left without new information for 30 days may be
closed. Reopening it with the missing detail is always fine and never held
against you.

---

## Security

**Please do not open a public issue for security vulnerabilities**.

Email **shadercraftpt@gmail.com** with the details and steps to reproduce.

---

## Ground rules

- Be civil and specific. Criticism of the software is welcome and useful;
  hostility toward people is not.
- One issue per report. Bundled lists are hard to track and partially close.
- English preferred.

Thank you for taking the time to file something — every good report makes the
tool better for everyone using it!

