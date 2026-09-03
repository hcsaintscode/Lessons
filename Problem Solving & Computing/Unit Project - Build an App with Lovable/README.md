# Unit Project — Build an App with Lovable

The capstone project for the **Problem Solving & Computing** unit. Students apply the two big ideas they learned — the **DPTR problem-solving process** (Define, Prepare, Try, Reflect) and the **IOSP model** (Input, Output, Storage, Processing) — to design, build, and ship a **real, working web app** that solves a problem *they* care about, using **[lovable.dev](https://lovable.dev)** (an AI app builder: describe an app in plain language, it generates and deploys a working web app to a public URL).

This is a **separate package** that sits alongside the weekly lessons — it does not replace Week 1 or Week 2. It's the "now build something real" payoff after Week 2's IOSP + app-design work.

## Why this project (student ownership)

Built to the Masterpiece Labs instructional-design principle: students see themselves as **creators and problem-solvers**, not assignment-completers.
- **Personalized:** each student chooses a real problem in their own life, family, school, or community.
- **Keepable & shareable:** the deliverable is a **deployed app at a public URL** — something they can keep and share.
- **Beyond the classroom:** students share the app with the real people who have the problem and gather feedback.
- **Reflective:** every guide closes with a personal-relevance reflection.

## The core idea: the IOSP spec *is* the prompt

The elegant bridge to lovable is that the **IOSP specification students write on paper becomes the prompt they give the AI.** Inputs, Outputs, Storage, and Processing map directly onto a clear build prompt. Planning the spec well is what makes the build succeed.

## Free-tier reality (design constraint)

lovable's free plan gives roughly **5 build credits per day, no rollover (~30/month)** ([Lovable docs](https://docs.lovable.dev/introduction/subscription-plans)). Every prompt costs a credit. The whole package is designed around this:
- **Plan the full spec on paper first** — no credits spent until the plan is complete.
- **One precise prompt beats ten vague ones.**
- **Out of credits for the day = a planning/iteration day** (reframed as a feature, not a failure).
- **MS** can run as small-group or teacher-driven builds to stretch credits; **HS** students/pairs drive lovable directly.

## Relationship to Week 2 (StackBlitz → Lovable)

Week 2's self-study had students hand-code a small `input → process → output` app in StackBlitz. That stays — it teaches what's happening under the hood. **Lovable is the same IOSP idea at full app scale, AI-generated.** HS students should be able to point to their app's inputs, processing, storage, and outputs in the running app, and their reflection compares what they *specified* vs. what the AI *produced*.

## Contents

```
Unit Project - Build an App with Lovable/
├── README.md                     ← this file
├── Middle School/
│   ├── teacher-guide.html        4 phase tabs: Setup · Define & Plan · Build & Iterate · Share & Reflect
│   ├── slides.html               12-slide launch + showcase deck
│   └── student-project-guide.html  printable workbook: DPTR → IOSP spec → build prompt → build log → reflection
└── High School/
    ├── teacher-guide.html        4 phase tabs: Setup · Define & Spec · Build & Iterate · Ship & Reflect
    ├── slides.html               13-slide launch + showcase deck
    └── student-project-guide.html  precise IOSP spec + build log + evaluate-AI-output + spec-vs-output reflection
```

### Middle School vs High School
| | Middle School | High School |
|---|---|---|
| Who drives lovable | Small groups or teacher-driven (stretches credits) | Each student/pair drives it directly |
| Framing | "Describe your app clearly; the AI builds it" | "Prompting is precise specification; you're the engineer directing the AI" |
| Spec depth | IOSP plan in plain language | Precise IOSP spec (data, controls, logic types, persistence) + peer spec review |
| Key deliverable | Working shared app + reflection | Working shared app + **build reflection comparing spec vs. AI output** + user testing |
| Evaluating output | "Does it work? Improve it." | Critically test the AI's output against the spec; verify logic with real inputs |

## Suggested pacing (~4–5 sessions, flexible)
1. **Setup** (~30 min) — accounts, credit budget, expectations.
2–3. **Define & Plan/Spec** (1–2 sessions) — DPTR + IOSP spec + build prompt, all on paper.
4–5. **Build & Iterate** (1–2 sessions) — spend credits deliberately; publish.
Final. **Share & Reflect** (1 session) — showcase, share with real users, reflect.

## Good project scopes
Trackers/planners, quiz or flashcard tools, sign-up or directory pages, decision helpers, simple dashboards — **one core feature done well.** Avoid payments, third-party logins/OAuth, or large datasets on the free tier.

## Safety & good practice
- No real personal data in student apps — use made-up test data.
- Review apps before sharing widely.
- Be mindful of what an app collects if others will use it.

## Free resources
| Resource | Use | Link |
|---|---|---|
| lovable.dev | The AI app builder students use | https://lovable.dev |
| Getting started | First app + publishing | https://docs.lovable.dev/introduction/getting-started |
| Publishing | Deploy to a shareable URL | https://docs.lovable.dev/features/publish |
| Plans & credits | Free-tier limits (for planning credit budget) | https://docs.lovable.dev/introduction/subscription-plans |

> Teacher guides, slides, and project workbooks are original Masterpiece Labs materials. lovable.dev is a third-party tool linked, not recreated. Confirm current free-tier limits before teaching, as pricing can change.
