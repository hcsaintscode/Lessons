# Pacing Calendar — Programming in App Lab

## Semester Arc Position: **Programming** (the phase where ideas become working software)
> Problem Solving → What Is a Computer? → Fabric of the Internet → **[Programming in App Lab]** → AI/ML → Cybersecurity → Global Impacts → Capstone

Students have learned a problem-solving process (DPTR), the IOSP model (Input → Processing → Storage → Output), how the Internet moves data, and — in the Problem Solving & Computing capstone — how to *describe* an app to an AI builder (Lovable). This unit is where they learn to **actually write the code** behind interactive apps: events, variables, input/output, conditionals, and functions.

**The through-line to Lovable:** By the end of this unit students can read and write event-driven code — so when an AI tool like Lovable generates an app, they can **direct it precisely and debug what it produces** instead of accepting it blindly. Programming literacy is what turns "AI made me an app" into "I can make the AI build *exactly* what I intended, and fix it when it's wrong."

**Source:** Code.org **Event-Driven Programming in App Lab** (`csp5-virtual`, Unit 1) — 11 lessons. This package sequences those lessons into a 4-week Learn/Explore/Create rhythm, supplies the teacher facilitation, smartboard slides, student worksheets, and self-study modules, and points to the real App Lab lessons for the plugged work.
Unit: https://studio.code.org/courses/csp5-virtual/units/1

---

## Environment (the blend)

| Track | Guided lessons | Self-study |
|-------|----------------|------------|
| **Middle School** | **App Lab** (visual Design Mode + drag-to-text JavaScript). Beginner-friendly; App Lab handles the UI/event plumbing. | No-login **StackBlitz** demo (plain-JS DOM events) — reinforces the same event → handler idea, self-contained. |
| **High School** | **App Lab in code mode** (text JavaScript). More independence, real functions/conditionals. | **StackBlitz** with plain-JS DOM events (`addEventListener`, buttons, inputs) — continues the Week 2 HS pattern, runs offline. |

> **Accounts:** Students have approved Code.org accounts for App Lab. The Code.org lessons are the plugged spine; our StackBlitz self-study modules require no login and run offline, so independent learners are never blocked.

**Schedule:** 1×45 (Learn) + 2×90 (Explore, Create) = 225 min/week. Learn introduces the concept + App Lab lesson; Explore is guided build time; Create is a "make it yours" build + reflection.

---

## The Code.org Unit (what we're mapping)

Event-Driven Programming in App Lab, Unit 1 — 11 lessons:
1. **Intro to App Lab** — Setting Properties · Make it Interactive · Images & Sounds · Design Mode
2. **Buttons and Events** — Debugging & Common Problems · setPosition & Screen Dimensions · Using Labels · Event Types · How Images Work · Chaser Game v.1
3. **Multi-screen Apps** — Debugging with `console.log` · Multi-Screen Chaser Game v.2 · **Project: Multi-Screen Chaser Game**
4. **Variables** — Intro to Variables (Pt 1 & 2) · Basic Mechanics · Other Ways to Assign Values · The Mental Model for Variables
5. **Building an App: Clicker Game** — Clicker Game Demo · App Lab Practice · Debugging Variables · Using Variables
6. **If-Statements** — Simple Decisions with if-statements
7. **User Input and Strings** — Mad Lib Demo · Strings in Apps · **Mad Lib Game**
8. **Boolean Expressions and "If" Statements** — Boolean Expressions · Comparison Operators · if / if-else Statements · Dropdown Menus
9. **"if-else-if" and Conditional Logic** — if-else-if · Compound Boolean Expressions (`&&`, `||`, `!`)
10. **Building an App: Color Sleuth** — RGB Colors · `setProperty` · Random Button/Color · Functions · Activating Buttons · Switch Player Turns · Updating the Score · **Project: Color Sleuth**
11. **Keep Going!**

---

## 4-Week Map

### Week 1 — Events: Making Things Interactive
**Big Idea:** An app reacts to *events* (like a button click). You set up the screen, then write an event handler that runs when the user acts. This is IOSP made real: input (click) → processing (handler) → output (screen changes).
**Code.org basis:** Lesson 1 (Intro to App Lab) + Lesson 2 (Buttons and Events).

| Day | Focus | Activity |
|-----|-------|----------|
| Day 1 — Learn | What is an event? Design Mode + `onEvent` | Set up a screen in Design Mode; add one button; write your first click handler |
| Day 2 — Explore | Event types, labels, properties; debugging basics | Multiple buttons/events; change labels & properties on click; intro to reading errors |
| Day 3 — Create | **Make it yours:** an interactive "about me" / reaction screen | Build a screen that responds to the user (buttons that change text, images, colors) + reflection |

**Deliverable:** A working interactive App Lab screen with at least two working events.
**MS:** Design Mode drag-drop + drag-to-text handlers. **HS:** code mode `onEvent(...)`. **Self-study (StackBlitz):** a button + `addEventListener` that changes the page.

---

### Week 2 — Variables & State: Apps That Remember
**Big Idea:** Variables let an app *remember and change* values — a score, a count, a name. Combined with events, you get an app with state (the Clicker Game). Also: debugging with `console.log`.
**Code.org basis:** Lesson 3 (Multi-screen Apps + `console.log` debugging) + Lesson 4 (Variables) + Lesson 5 (Clicker Game).

| Day | Focus | Activity |
|-----|-------|----------|
| Day 1 — Learn | What is a variable? The mental model (a labeled box) | Declare, assign, update a variable; show it on screen |
| Day 2 — Explore | Variables + events = state; `console.log` debugging | Build the Clicker Game: a button that increments a score variable and displays it |
| Day 3 — Create | **Make it yours:** a counter/tracker app for something *you* care about | A tally app (water, push-ups, reading minutes, chores) + reflection |

**Deliverable:** A working Clicker/counter app that updates a variable on events and displays it.
**MS:** guided Clicker Game, personalize the theme. **HS:** code mode, add a reset + a second variable. **Self-study (StackBlitz):** a click-counter with a `count` variable + reset.

---

### Week 3 — Input & Decisions: Apps That Respond to You
**Big Idea:** Read user input (text boxes, dropdowns), work with strings, and make decisions with conditionals (`if` / `if-else` / `if-else-if`) and Boolean logic (`==`, `>`, `&&`, `||`, `!`). This is the "Processing" of IOSP getting smart.
**Code.org basis:** Lesson 6 (If-Statements) + Lesson 7 (User Input & Strings / Mad Lib) + Lesson 8 (Boolean Expressions & If) + Lesson 9 (if-else-if & Compound Logic).

| Day | Focus | Activity |
|-----|-------|----------|
| Day 1 — Learn | Reading input + strings; simple `if` decisions | Read a text input, combine strings, show a personalized output (Mad Lib style) |
| Day 2 — Explore | Boolean expressions, comparison operators, if-else, dropdowns | A decision screen: input/dropdown → `if-else` → different outputs |
| Day 3 — Create | **Make it yours:** a decision app (quiz, recommender, mood/advice) | if-else-if + compound conditions (`&&`/`||`) driving real choices + reflection |

**Deliverable:** An app that takes input and uses conditionals to produce different outputs.
**MS:** Mad Lib + a simple `if` picker. **HS:** code mode, compound conditions, a small quiz with scoring. **Self-study (StackBlitz):** an input + dropdown → `if-else-if` → rendered result.

---

### Week 4 — Functions, a Real App & the Bridge to AI
**Big Idea:** Functions package logic you reuse (pick a random color, update the score). Put events + variables + conditionals + functions together into a complete app (Color Sleuth). Then connect it forward: because you can now read and write this code, you can *direct and debug* an AI builder like Lovable.
**Code.org basis:** Lesson 10 (Building an App: Color Sleuth — functions, random, activating buttons, scoring, project) + Lesson 11 (Keep Going!).

| Day | Focus | Activity |
|-----|-------|----------|
| Day 1 — Learn | Functions (define/call), randomness, `setProperty` | Write & call a function; make a random color/button |
| Day 2 — Explore | Assemble a full app: events + variables + conditionals + functions | Build Color Sleuth (or a scoped version): activate buttons, switch turns, update score |
| Day 3 — Create | **Capstone build + Lovable bridge:** a self-chosen event-driven app; then compare hand-coding vs. directing an AI | Ship a small app; reflection: "what would I now tell Lovable to build, and how would I debug what it returns?" |

**Deliverable:** A complete, self-chosen event-driven app (functions + variables + conditionals + events) + a written reflection connecting hand-coding to directing/debugging AI-generated code.
**MS:** guided Color Sleuth, personalize; light functions. **HS:** code mode, write multiple functions, self-chosen app. **Self-study (StackBlitz):** a function-driven mini-app (e.g., random-color guessing game) + the Lovable-bridge reflection.

---

## Student Ownership (applied throughout)
- Every **Create** day is a "make it yours" build on a self-chosen theme (about-me screen, a tracker for something they do, a quiz/recommender they care about, a capstone app of their choice).
- Deliverables are **keepable**: App Lab projects (shareable link) and StackBlitz projects.
- **Extend beyond the classroom:** share the app link with a friend/family member; add a feature at home.
- **Personal-relevance reflection** each week; the Week 4 reflection explicitly ties programming literacy to directing/debugging AI tools.

## Assessment
| Component | Weight | How |
|-----------|--------|-----|
| Participation / labs | 25% | Engagement in App Lab build time |
| Worksheets / build logs | 20% | Plan + trace + debug notes completed |
| Weekly build deliverable | 40% | The working app each week (rubric in each teacher-guide) |
| Reflection | 15% | Personal-relevance + (Week 4) the AI-bridge reflection |

## Free Resources
| Resource | Where it fits | Link |
|----------|---------------|------|
| Code.org — Event-Driven Programming in App Lab (Unit 1) | The plugged spine; App Lab environment | https://studio.code.org/courses/csp5-virtual/units/1 |
| App Lab (standalone) | Building/testing apps | https://code.org/educate/applab |
| lovable.dev | The AI-builder callback in Week 4 | https://lovable.dev |

> Content adapted from Code.org's Event-Driven Programming in App Lab unit. App Lab lessons are linked, not recreated. Teacher guides, slides, worksheets, and the StackBlitz self-study modules are original Masterpiece Labs materials.

---

## File Inventory
```
Programming in App Lab/
├── 00_Pacing_Calendar.md            ← this file
├── Week 01/ { Middle School, High School } × { teacher-guide, slides, student-worksheet, self-study }
├── Week 02/ { Middle School, High School } × { … }
├── Week 03/ { Middle School, High School } × { … }
└── Week 04/ { Middle School, High School } × { … }
```
