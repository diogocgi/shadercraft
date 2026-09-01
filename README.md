# ShaderCraft Alpha v0.1.0

<img width="1659" height="846" alt="image" src="https://github.com/user-attachments/assets/fe91c63d-315d-40bb-bce4-2104fe50420d" />


Welcome! This repository is the **public issue tracker** for **ShaderCraft** — an
infinite node canvas hosting focused studios for painting, photo development,
vector work, animation, 3D and more!

**The app is available at shadercraft.com** — the only official site.

---

## What to open here

Use **New issue** on the tracker — blank issues are turned off, so every report
starts from one of the forms below.

| I want to… | Open |
|---|---|
| Report something broken, wrong, or crashing | **Bug report** |
| Report a rendering / performance problem | **Bug report** — fill in the *Rendering / performance details* section |
| Ask for a new feature, tool, or format | **Feature request** |
| Ask how something works, or whether it is possible | **Discussion** (if enabled) or the **Question** form |
| Report a security vulnerability | **Do not open an issue** — see [Security](#security) |

Every form starts with the same checkbox: **search the existing issues first**,
including closed ones. If you find a match, add a 👍 or a comment on it instead
of opening a duplicate — feature requests are prioritised partly by reactions.

---

## Reporting a bug

The **Bug report** form asks for everything I need to reproduce a problem without
follow-up questions:

1. **What happened** — what went wrong, and what you expected instead.
2. **Steps to reproduce** — the exact clicks, from a fresh document where possible.
3. **Where in the app** — Workspace, Paint, Photo, Vector, Animation, Diagram,
   Mesh Viewer, Meshgen, Mesh Paint, Parametric, Assembly, Gears, Diorama,
   Pixel Wall Art, Studio or Website. "Not sure" is a valid answer.
4. **How you are running it** — in a browser, or the desktop app.
5. **Version** — the version number shown in the app.
6. **Browser, OS and GPU** — e.g. `Chrome 141, Windows 11, NVIDIA RTX 3060`.
   Your GPU is listed at `chrome://gpu` (Chrome/Edge) or `about:support` (Firefox).
7. **Console errors** — open devtools (F12), reproduce the bug, paste anything red.
8. **Rendering / performance details** — only for slowness, stutter, or something
   drawn incorrectly: document size (canvas resolution, layer count, mesh triangle
   count), what makes it slow (painting, panning, playback, export), and whether it
   was ever faster.
9. **Screenshots, recordings, or a `.shc` file** — for anything visual, a short
   screen recording explains more than any description. Drag files into the box to
   attach them. Attach the project file if the bug depends on a specific document
   and you are happy to share it.

### Extra detail that helps a lot

- **Does it reproduce every time**, or only sometimes? Only on large documents?
  Only after a particular action?
- **Data loss / autosave issues**: say whether the document had been saved,
  reloaded, or restored, and roughly how large it was. These get top priority.

---

## Requesting a feature

The **Feature request** form asks for the **problem**, not only the solution:

- **What are you trying to do** — the real task you are stuck on, in your words.
  This is the most useful part of the request.
- **What would you like ShaderCraft to do** — the feature as you imagine it.
  Rough is fine.
- **Where it belongs** — a mode, *Import / export formats*, *Across the whole app*,
  or "Not sure".
- **How you do it today** — the workaround you use, in ShaderCraft or another app,
  and why it is not good enough.
- **References** — sketches, screenshots, or another tool that does this well
  (Photoshop, Illustrator, Lightroom, Affinity, Blender, Figma, Krita,
  After Effects…). Naming the tool and the feature is a big shortcut for me.

---

## Asking a question

If Discussions are open on the tracker, prefer them for open-ended conversation —
they thread better. Use the **Question** form when you want a direct answer. It
asks for the question, where in the app it applies, and what you have already
tried. Please check the in-app documentation and the existing issues first.

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
| `enhancement` | New capability, or an improvement to something that already exists |
| `question` | A question rather than a defect or a request |
| `perf` | Speed, memory, or responsiveness |
| `rendering` | WebGL / GPU / driver-specific |
| `ux` | Workflow, layout, discoverability |
| `docs` | Improvements or additions to documentation |
| `duplicate` | Tracked elsewhere — see the linked issue |
| `wontfix` | Deliberately out of scope (always with a reason) |
| `shipped` | Fixed or implemented in a released build |
| `accessibility` | Barrier affecting people with disabilities |

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

**Please do not open a public issue for security vulnerabilities.**

Report it privately, in either of these ways:

- The **Report a vulnerability** button under the tracker's **Security** tab, which
  opens a private advisory only the maintainers can see.
- Email **shadercraftpt@gmail.com** with `SECURITY` in the subject line.

The full policy — what is in and out of scope, what to include, and what to avoid
testing — is in [SECURITY.md](.github/SECURITY.md).

---

## Ground rules

- Be civil and specific. Criticism of the software is welcome and useful;
  hostility toward people is not.
- One issue per report. Bundled lists are hard to track and partially close.
- English preferred.

Thank you for taking the time to file something — every good report makes the
tool better for everyone using it!

