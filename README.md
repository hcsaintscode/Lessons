# Masterpiece Labs — Technology Curriculum 2027

The course home is **`index.html`** — open it in a browser (or visit the published GitHub Pages URL) to navigate every lesson: filter by unit, level (Middle / High School), and file type, or search by keyword.

## Units
- **Problem Solving & Computing** — the problem-solving process, the IOSP model, and a capstone app build with lovable.dev.
- **The Fabric of the Internet** — how the Internet moves data, finds websites, and who gets access.
- **Programming in App Lab** — event-driven programming (events, variables, conditionals, functions) built in Code.org App Lab, culminating in a student-chosen app. Framed as the bridge to *directing and debugging* what an AI like Lovable generates: once you understand events and variables, you can steer and fix AI-built code.

Each week has a **Middle School** and **High School** track, each with a teacher guide, slides, worksheet, and self-study module. Some self-study modules embed a live StackBlitz code editor (all four Programming self-study modules do, plus some High School modules in other units).

---

## Publishing to GitHub Pages

GitHub Pages serves a repository (or a folder in it) as a website. There are two common setups.

### Option A — this folder is the repository root
1. Create a new GitHub repo and push the contents of this `2027` folder to it (so `index.html` sits at the repo root).
2. In the repo: **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Pick branch **`main`** and folder **`/ (root)`**, then **Save**.
5. Wait ~1 minute. Your site appears at `https://<your-username>.github.io/<repo-name>/`.

### Option B — publish from a subfolder of an existing repo
If `index.html` lives in a subfolder, in **Settings → Pages** choose the branch and set the folder to `/docs` (GitHub only supports `/` or `/docs` as the source folder). The simplest path is to rename/place this content so `index.html` is at the repo root or in a `docs/` folder.

### Notes that matter for this site
- **`.nojekyll`** is included so GitHub Pages serves all files as-is (it skips Jekyll processing). Keep it.
- **Folder names contain spaces and `&`.** The links in `index.html` are already percent-encoded (`%20`, `%26`) so they work on GitHub Pages. If you rename folders, update the links.
- **Everything is static** — no build step, no dependencies to install. The only external calls are Google Fonts, YouTube links, the Pew/Code.org reference links, and (in the HS coding self-study modules) the StackBlitz SDK. All require internet access at view time.
- **Relative links** are used throughout, so the site works whether it's at a domain root or under `/<repo-name>/`.

### Quick local preview
From this folder:
```
python3 -m http.server 8000
```
Then open `http://localhost:8000/` in your browser. (A plain double-click of `index.html` also works, though a local server most closely matches how GitHub Pages serves it.)

---

## File map
```
2027/
├── index.html                         ← course home / navigation
├── .nojekyll
├── README.md
├── Problem Solving & Computing/
│   ├── 00_Pacing_Calendar.md
│   ├── Week 01/ { Middle School, High School } × {teacher-guide, slides, student-worksheet, self-study}
│   ├── Week 02/ { Middle School, High School } × {teacher-guide, slides, student-worksheet, self-study}
│   └── Unit Project - Build an App with Lovable/
│       ├── README.md
│       └── { Middle School, High School } × {teacher-guide, slides, student-project-guide}
├── Fabric of the Internet/
│   ├── 00_Pacing_Calendar.md
│   ├── Week 01/ { Middle School, High School } × {teacher-guide, slides, student-worksheet, self-study}
│   └── Week 02/ { Middle School, High School } × {teacher-guide, slides, student-worksheet, self-study}
└── Programming in App Lab/
    ├── 00_Pacing_Calendar.md
    ├── Week 01/ { Middle School, High School } × {teacher-guide, slides, student-worksheet, self-study}  ← Intro to App Lab + Buttons & Events
    ├── Week 02/ { Middle School, High School } × {teacher-guide, slides, student-worksheet, self-study}  ← Multi-screen apps + Variables + Clicker Game
    ├── Week 03/ { Middle School, High School } × {teacher-guide, slides, student-worksheet, self-study}  ← User Input & Strings + Conditionals
    └── Week 04/ { Middle School, High School } × {teacher-guide, slides, student-worksheet, self-study}  ← Functions + Color Sleuth + student-chosen project + Lovable bridge (Capstone)
```
