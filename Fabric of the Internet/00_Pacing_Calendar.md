# Pacing Calendar — The Fabric of the Internet

## Semester Arc Position: bridge unit between **Problem Solving** and **Programming**
> Problem Solving → **[Fabric of the Internet]** → Programming → AI/ML → Cybersecurity → Global Impacts → Capstone

Students have learned a problem-solving process (Week 1) and that every computer is Input/Processing/Storage/Output (Week 2). Before they start programming, this unit answers the question hiding behind every app they'll ever build: **how does data actually get from one machine to another across the world?** It also seeds two later phases — Cybersecurity (network security lessons) and AI/ML (AI's role in networking) — so the arc stays connected.

**Length:** 2 weeks core (6 sessions). An optional **Week 3 extension** covers network security + AI, which previews the Cybersecurity phase.

---

## Source Material (in `Raw Files/`)

| Source | What it is | How this unit uses it |
|--------|-----------|------------------------|
| `The-Fabric-of-the-Internet-and-AI.pdf` | Code.org **AI Foundations · Unit 3** — 11 lessons, 3 weeks. Teaches Internet infrastructure with an AI-in-networking overlay + the Internet Simulator widget. | Primary spine for the **middle school** track and the AI-flavored extension. |
| `The-Fabric-of-the-Internet-and-AI-Resources.pdf` | The student **Unit Guide** + activity guides (vocab tables, IP routing table, network-diagram analysis, Pew digital-divide data, advocacy personas, security vulnerability cards, threat-detection notetaker). | Source of hands-on activities and worksheets for both tracks. |
| `CSP Unit 2 - The Internet.pdf` | Code.org **CS Principles** — 8 lessons. Same core networking concepts, more rigorous/AP-aligned, no AI overlay, ends with the "Internet Dilemmas" project. | Primary spine for the **high school** track (more technical, protocol-focused). |

**Approach:** SUPPLEMENT + REPLACE hybrid. The core concepts and hands-on labs (many are *unplugged* — string networks, binary hand-signals, packet simulation) come from Code.org and are excellent as-is. Our Masterpiece Labs package provides the teacher facilitation guide, smartboard slides, a student worksheet, and a self-study module that make the concepts learnable without a Code.org login where possible, and point to the Code.org **Internet Simulator** widget where the plugged activities require it.

> Note on the Internet Simulator: Lessons that use Code.org's Internet Simulator widget (IP addressing, routers, packets, DNS) require a Code.org account. Those are flagged **[Sim]** below. The unplugged lessons (Sending Bits, the security card sort, digital-divide discussion) need no login.

---

## Both tracks meet 3×/week: 1×45 (Learn) + 2×90 (Explore, Create) = 225 min/week

The Code.org lessons are mostly 45 minutes each, so our 45/90/90 structure lets us pair lessons on the long days and still leave room for a Masterpiece Labs hands-on build or discussion.

## Design Principle: Student Ownership & Personalization

Every activity in this unit is built so students take ownership and see themselves as creators and problem-solvers, not just assignment-completers. Concretely, in this unit:
- **Map *their* Internet.** Students diagram how *their own* home/school/phone actually connects (their devices, their router, their apps) rather than a generic textbook network.
- **Choose what they investigate.** The digital-divide and Internet-Dilemmas work lets students pick the issue, community, or persona that matters to them — ideally one touching their own family, neighborhood, or school.
- **Make something they can keep or use.** The advocacy campaign (MS) and Internet Dilemmas position (HS) are real, sharable artifacts students can present beyond class (to family, a school board, a club).
- **Extend beyond the classroom.** Prompts invite students to test ideas at home (trace a real DNS lookup on their own device, spot redundancy or a "digital divide" moment in their own life).
- **Reflect on personal relevance.** Each week closes with a reflection on how understanding the Internet changes how they use it in their own life.

(This mirrors the workspace-wide instructional design steering; it's restated here so the unit's builders keep it front of mind.)

---

# MIDDLE SCHOOL TRACK (2 weeks)

**Driving Question:** How does the Internet move data from one device to another across the world — reliably, and for (almost) everyone?

**Framing:** concrete, hands-on, lots of unplugged simulation. Lighter on protocol formalism; heavier on "act it out and see it."

### Week 1 — How the Internet Moves Data
| Day | Length | Focus | Code.org basis | Activity |
|-----|--------|-------|----------------|----------|
| Day 1 — Learn | 45 | What *is* the Internet? Routers, switches, servers, towers | Lesson 1: Intro to the Internet | Vocab + "connect two devices across the world" discussion; intro the Internet Simulator **[Sim]** |
| Day 2 — Explore | 90 | Bits & how messages travel; addresses | Lesson 2: Sending Bits (unplugged) + Lesson 3: IP Addresses **[Sim]** | Human-network string activity + binary hand-signal transmission; then IP routing-table read |
| Day 3 — Create | 90 | Getting there reliably: routers, redundancy, packets | Lesson 4: Routers & Redundancy **[Sim]** + Lesson 5: Packets (unplugged + **[Sim]**) | Network-diagram analysis + packet-loss simulation; "design a reliable route" challenge |

### Week 2 — Finding Websites & Who Gets Access
| Day | Length | Focus | Code.org basis | Activity |
|-----|--------|-------|----------------|----------|
| Day 1 — Learn | 45 | How your browser finds a website | Lesson 6: HTTP & DNS **[Sim]** | DNS "phone book" analogy; classroom IP-address collection; DNS query simulation |
| Day 2 — Explore | 90 | The digital divide & net neutrality | Lesson 7: The Internet's Hidden Barriers | Pew Research data read + persona case-study (Diego, Lisa, Mr. Johnson, Aisha) |
| Day 3 — Create | 90 | Advocacy campaign (unit deliverable) | Lesson 8: Internet Access Advocacy Campaign | Gallery walk → build & present a short advocacy campaign for digital equity |

**MS Deliverable:** an Internet Access Advocacy Campaign (poster/slides) + a completed Unit Guide (vocab + Questions of the Day).

---

# HIGH SCHOOL TRACK (2 weeks)

**Driving Question:** What protocols and design principles let an unreliable, decentralized network deliver data correctly — and what dilemmas does that create?

**Framing:** protocol-level rigor (TCP/UDP tradeoffs, IP addressing, DNS hierarchy, redundancy as a design principle), drawing on the CSP Unit 2 spine. Ends with a reasoned "Internet Dilemmas" position rather than a poster.

### Week 1 — Building a Reliable Network
| Day | Length | Focus | Code.org basis (CSP + AI Found.) | Activity |
|-----|--------|-------|----------------------------------|----------|
| Day 1 — Learn | 45 | The Internet as a layered system | CSP L1 Welcome + L2 Building a Network | Why a decentralized network? Fully-connected vs. scalable topologies (string activity framed as a scaling problem) |
| Day 2 — Explore | 90 | Addressing & routing | CSP L3 Need for Addressing + L4 Routing & Redundancy **[Sim]** | IP addressing lab + network-diagram analysis; redundancy & single-point-of-failure challenge |
| Day 3 — Create | 90 | Protocols: packets, TCP vs UDP | CSP L5 Packets **[Sim]** | Packet simulation; design a reliability protocol; formalize the TCP/UDP speed-vs-reliability tradeoff |

### Week 2 — The Web, and the Dilemmas It Creates
| Day | Length | Focus | Code.org basis | Activity |
|-----|--------|-------|----------------|----------|
| Day 1 — Learn | 45 | DNS hierarchy & HTTP request/response | CSP L6 HTTP & DNS **[Sim]** | DNS resolution walkthrough; inspect a real HTTP request (browser dev tools) |
| Day 2 — Explore | 90 | Net neutrality, the digital divide, data ethics | AI Found. L7 Hidden Barriers + CSP L7 framing | Pew data analysis + structured debate positions |
| Day 3 — Create | 90 | Internet Dilemmas (unit deliverable) | CSP L7 Project: Internet Dilemmas | Research a dilemma (net neutrality, censorship, access, privacy) → write & present a reasoned position |

**HS Deliverable:** an Internet Dilemmas position paper/presentation (claim + evidence from network principles and real data) + a technical concept check (addressing, routing, TCP/UDP, DNS).

---

## Optional Week 3 Extension — Network Security & AI (previews the Cybersecurity phase)
Both tracks, if you have the time and want to foreshadow later units:
| Day | Focus | Code.org basis |
|-----|-------|----------------|
| Learn | Network vulnerabilities: phishing, weak passwords, default credentials, social engineering | AI Found. L9: Network Security (vulnerability card sort) |
| Explore | How AI detects threats vs. traditional methods | AI Found. L10: Emerging Technologies (Threat Detection notetaker) |
| Create | Network Security Risk Assessment | AI Found. L11: Risk Assessment Project |

---

## Key Vocabulary (unit-wide)
router · switch · server · Internet tower · bit · binary · protocol · **TCP** (reliable, ordered) · **UDP** (fast, no guarantee) · IP address · packet · redundancy · **DNS** · **HTTP** · net neutrality · digital divide · (extension: phishing, vulnerability, mitigation, anomaly, false positive)

## Assessment
| Component | Weight | How |
|-----------|--------|-----|
| Participation / labs | 25% | Engagement in the unplugged simulations + Internet Simulator activities |
| Unit Guide / worksheet | 20% | Vocab + Questions of the Day completed |
| Concept check | 20% | Short check on addressing, routing, packets, DNS |
| Unit deliverable | 35% | MS: advocacy campaign · HS: Internet Dilemmas position |

## Free Resources
| Resource | Where it fits | Link |
|----------|---------------|------|
| Code.org — "The Internet: Wires, Cables & WiFi" (video) | Week 1 hook for Sending Bits | https://www.youtube.com/watch?v=ZhEf7e4kopM |
| Code.org AI Foundations Unit 3 (Fabric of the Internet) | MS spine + Internet Simulator widget | https://studio.code.org/courses/ai-foundations-year1-2026 |
| Code.org CS Principles Unit 2 (The Internet) | HS spine + Internet Simulator | https://studio.code.org/courses/csp-2026 |
| Pew Research Center — Internet/Broadband fact sheet | Digital-divide data (both tracks, Week 2) | https://www.pewresearch.org/internet/fact-sheet/internet-broadband/ |

> Content adapted from Code.org's AI Foundations Unit 3 and CS Principles Unit 2 (CC BY-NC-SA 4.0). Videos and the Internet Simulator are linked, not recreated. Teacher guides, slides, worksheets, and self-study modules are original.

---

## File Inventory (to be built after questions below are answered)
```
Fabric of the Internet/
├── 00_Pacing_Calendar.md            ← this file
├── Week 01/  { Middle School/, High School/ }  each: teacher-guide, slides, student-worksheet, self-study
└── Week 02/  { Middle School/, High School/ }  same four files
```
