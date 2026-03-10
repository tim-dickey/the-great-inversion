# How the Playbook Audit Works

The audit scores in this repository (68/100 composite, Priority 1–3 fixes, v3 bias corrections) come from a structured diagnostic process—not vibes, not "I think it's pretty good."

Here's how the audit works, why the scores dropped from v2 to v3 (and why that's good), and what you should actually trust about this process.

---

## The Seven Frameworks (And Why There Are Seven)

This playbook was evaluated using a diagnostic model I adapted from McDonald (2026)—a multi-framework audit suite designed for practitioner-focused content, not academic research papers.

Why seven frameworks instead of one? Because **your decision to trust this playbook isn't one-dimensional**. You're not just asking "Is this accurate?" You're asking:
- Can I actually learn this in my context?
- Will this work in my org's culture?
- Does this address my real job, or some idealized version?
- Can I admit I don't know this stuff without looking incompetent?
- Are the claims substantiated, or is this consultant hand-waving?

A guide that scores 95/100 on technical accuracy but 20/100 on psychological safety won't get used. It'll sit in your downloads folder while you feel vaguely guilty about not reading it.

The audit integrates seven established frameworks to catch those gaps:

### 1. Structural Architecture (Software Engineering + Instructional Design)
**What it measures:** Content organization, learning pathways, cognitive load management  
**Based on:** Merrill's First Principles of Instruction, modular design theory  
**Questions:** Does the content scaffold complexity progressively? Can readers navigate to what they need? Is the structure intuitive for time-starved practitioners?

### 2. Adoption Intelligence (Innovation Diffusion Research)
**What it measures:** How well content addresses adoption barriers across the innovator→laggard spectrum  
**Based on:** Rogers' Diffusion of Innovations (2003), Moore's Crossing the Chasm (1991)  
**Questions:** Does this work for early adopters AND skeptical pragmatists? Does it help navigate team diversity in AI readiness?

### 3. Psychological Safety (Organizational Learning Theory)
**What it measures:** Whether content creates safe environment for skill-gap acknowledgment  
**Based on:** Edmondson's team psychological safety research (1999-2023), Brown's vulnerability research (2012-2023)  
**Questions:** Can readers admit confusion without feeling incompetent? Is failure reframed as learning? Are status threats mitigated?

### 4. Organizational Behavior Validity (Culture & Change Management)
**What it measures:** Applicability across diverse org cultures and change readiness levels  
**Based on:** Schein's organizational culture models, Kotter's change management frameworks  
**Questions:** Does this only work in psychologically-safe tech startups, or also in regulated/low-trust environments? Are structural barriers acknowledged?

### 5. Job Architecture (Jobs-to-be-Done Framework)
**What it measures:** Alignment between content and the actual "jobs" target roles need to accomplish  
**Based on:** Christensen's Jobs-to-be-Done theory, Ulwick's Outcome-Driven Innovation  
**Questions:** Does this address the real job (managing scope creep, stakeholder politics, sprint chaos) or an idealized version? Does it fit actual workflow constraints?

### 6. Empirical Rigor (Social Science Research Standards)
**What it measures:** Claim substantiation, citation quality, provenance disclosure  
**Based on:** APA research standards, evidence-based practice criteria  
**Questions:** Are claims backed by evidence? Are sources credible? Is provenance complexity acknowledged (e.g., vendor-preferred narratives)?

### 7. Displacement Risk Framing (Labor Economics + Adult Learning Theory)
**What it measures:** How content addresses career displacement concerns and skill obsolescence  
**Based on:** Autor's labor market research, Mezirow's transformative learning theory  
**Questions:** Are career risks named honestly? Is agency provided alongside risk disclosure? Is dignity preserved while discussing displacement?

---

## Why These Specific Frameworks

Most AI adoption guides optimize for one thing: **not being wrong**. They pass technical review, cite all the right papers, and land in your downloads folder where they die quietly.

This audit evaluates seven dimensions because your actual decision to USE this playbook weighs all of them simultaneously:

- **Structural Architecture:** Can I learn this without a PhD in AI? Is the content organized for how I actually learn?
- **Adoption Intelligence:** Will this help me work with both the excited early adopters AND the skeptical veterans on my team?
- **Psychological Safety:** Can I admit I'm confused without feeling incompetent?
- **Organizational Behavior Validity:** Will this work in MY org culture, or only in psychologically-safe tech startups?
- **Job Architecture:** Does this address my real job (managing scope creep, stakeholder politics, sprint chaos) or an idealized version where I have infinite time?
- **Empirical Rigor:** Are the claims actually substantiated, or am I being sold a vendor narrative?
- **Displacement Risk Framing:** Does this acknowledge my career concerns honestly, or gaslight me with "AI will only help you" platitudes?

**A guide that scores 95/100 on accuracy but 20/100 on psychological safety won't get read.** This audit catches that.

---

## Who Conducted This Audit (And Why You Should—or Shouldn't—Trust It)

**The honest answer:**
- Primary evaluation: Me (Tim Dickey, the author) using the McDonald (2026) diagnostic suite
- External review: E. McDonald (methodology designer, independent consultant)  
- Practitioner validation: 20+ Product Owner/PM/SM interviews that informed the scoring rubrics

**The potential bias:**
Yes, I audited my own work. That creates inherent confirmation bias risk—I'm incentivized to score myself well.

**Why I did it anyway:**
This is a **formative audit** (improving the work) not a **summative audit** (certifying quality for a journal). Think of it like a code review where the developer is in the room—you get faster iteration, better context, and the person who can actually FIX the issues is present.

**The mitigations:**
- External consultant review (McDonald) to challenge my scoring
- Explicit bias layer added in v3 audit (Research Bias findings you see in the repo)
- Documented rubrics so you can see HOW scores were derived, not just trust the numbers

**What you're trusting:**
You're not trusting secret methodology. The frameworks listed above are established research traditions—Edmondson's psychological safety work, Rogers' diffusion research, Christensen's Jobs-to-be-Done. You're trusting my *application* of those frameworks to this playbook.

**The bottom line:**
Judge this playbook by USING it. The audit just shows you how I made quality decisions. If the audit scores were perfect but the playbook didn't help you, the scores would be meaningless.

---

## Sample Scoring Rubric: Psychological Safety Dimension

To show how judgments are made, here's the rubric for **one dimension** in detail:

**What we're measuring:**  
Does the content create an environment where readers can acknowledge skill gaps, admit confusion, and ask "dumb questions" without status threat?

**Scoring criteria (0-100 scale):**

| Score Range | Indicators | Example Signals |
|-------------|-----------|-----------------|
| **90-100** | Vulnerability explicitly normalized. Status-threat mitigation built into structure. Failure reframed as learning. Multiple safety cues throughout. | "Most PMs I interviewed said they felt dumb asking about tokens. You're not dumb—the terminology is genuinely confusing, and the people who designed it didn't prioritize clarity." |
| **70-89** | Empathy present but inconsistent. Assumes moderate psychological safety already exists in reader's context. Some status threat remains unaddressed. | "Don't worry if you don't understand this yet." *(Implies you SHOULD understand it soon, creating timeline pressure)* |
| **50-69** | Neutral tone. Doesn't create safety, doesn't actively threaten status. Reader must bring their own psychological safety to the learning process. | Technical explanation with no emotional scaffolding or vulnerability normalization. |
| **30-49** | Inadvertent status threat. Implies knowledge gaps are individual failing rather than normal learning process. "Just learn this" framing without support. | "This is simple if you understand the basics." *(Reader thinks: "I don't understand the basics = I'm not qualified for my role")* |
| **0-29** | Active status threat. Shaming language. Competence gatekeeping. Implies current practitioners who don't know this are behind or failing. | "Anyone who doesn't know this by now is already behind. You need to catch up fast or risk irrelevance." |

**This playbook's score: 82/100**  

**Strengths:**  
- Strong empathy and vulnerability normalization in narrative sections
- Explicit "you're not late" framing counters urgency-driven anxiety
- "In the voice of..." sections show real practitioners learning imperfectly
- Failure stories included alongside success patterns

**Weaknesses:**  
- Some templates assume pre-existing team psychological safety (e.g., "bring this to your retro" assumes retros are psychologically safe spaces—not universal in all org cultures)
- Occasional "just try this" language that underestimates organizational barriers
- Could more explicitly name structural reasons for skill gaps (limited training budgets, velocity pressure) vs. individual learning capacity

**Why this matters:**  
Product Owners reading this alone at 11pm wondering if they're qualified for their jobs need more than accurate information. They need permission to not know, explicit normalization of confusion, and structural (not individual) explanations for why they're behind. An 82/100 means we're doing well but missing edge cases.

---

## Why Version 3 Changed the Scoring Weights

The v2 audit scored this playbook at **71/100**. Version 3 scored it at **68/100**—and that *drop* is a good thing. Here's why.

**What changed:**  
V2 over-weighted **Empirical Rigor** (statistical evidence, citation quality) relative to **Organizational Behavior Validity** and **Psychological Safety**. That weighting made sense for academic research guides, but this isn't an academic research guide.

**The recalibration logic:**  
Your decision to apply this playbook in your team doesn't hinge primarily on citation counts. It hinges on:
- Whether your org culture will support the practices (Behavior Validity)
- Whether you feel safe admitting skill gaps while learning (Psychological Safety)  
- Whether the guidance matches your actual job constraints (Job Architecture)

V3 rebalanced to favor **practitioner usability over academic purity**. A playbook that's 90% empirically rigorous but 40% culturally applicable won't help you. A playbook that's 75% empirically rigorous but 80% culturally applicable *will*.

**The score drop is a feature, not a bug:**  
The lower composite score reflects more honest weighting of what actually matters for your adoption decision. I'd rather give you an accurate 68/100 than an inflated 71/100 that hides usability gaps.

**What this means for you:**  
The Priority 1–3 fixes and v3 bias corrections weren't triggered by the score drop—they were triggered by the recalibrated lens revealing gaps v2 missed. You're getting a better product because the audit got more honest.

**V3 weighting distribution:**
- Psychological Safety: 20% (up from 12% in v2)
- Organizational Behavior Validity: 18% (up from 10% in v2)
- Job Architecture: 16% (up from 12% in v2)
- Empirical Rigor: 15% (down from 25% in v2)
- Structural Architecture: 13% (maintained)
- Adoption Intelligence: 10% (maintained)
- Displacement Risk Framing: 8% (maintained)

The shift prioritizes "will this work in messy real-world conditions" over "is every claim perfectly cited."

---

## Additional Framework Enhancement (Optional)

**Note on Psychological Safety:** The v3 audit integrates both **Edmondson's team-level psychological safety** (can I speak up in team contexts without punishment?) and **Brené Brown's individual-level vulnerability research** (can I show up imperfect and still belong?).

This dual-lens approach recognizes that Product Owners consume this playbook in two contexts:
1. **Team settings** (bringing AI topics to sprint ceremonies) → Edmondson's framework
2. **Solo learning** (reading alone, wondering if skill gaps mean they're unqualified) → Brown's framework

The 82/100 Psychological Safety score reflects both lenses. If we scored using Edmondson alone, the playbook would rate higher (~88/100) because team-context safety is well-addressed. If we scored using Brown alone, it would rate lower (~76/100) because solo-reader vulnerability mitigation has gaps.

The composite 82/100 is the honest middle ground.

---

## Should You Trust This Audit?

Here's my take: **Use this audit as a transparency signal, not a quality certificate.**

The scores show you I took quality seriously enough to run a structured assessment before publishing. The Priority fixes show you I acted on what I found. The v3 recalibration shows you I adjusted when the methodology revealed gaps.

But trust the *playbook* by using it, not by trusting the scores. If this guide helps you have better AI-fluent conversations with your dev team next week, the audit worked. If it sits in your downloads folder, no amount of 68/100 scores will matter.

That's the deal.

---

## Excalidraw Diagrams

The following diagrams are available as editable Excalidraw source files:

- Framework Lens Map: `docs/diagrams/excalidraw/framework-lens-map.excalidraw.json`
- V2 to V3 Weight Shift: `docs/diagrams/excalidraw/v3-weight-shift.excalidraw.json`
- Trust to Adoption Flow: `docs/diagrams/excalidraw/trust-to-adoption-flow.excalidraw.json`

Suggested use:
- Embed static exports (PNG/SVG) in this doc for fast scanning.
- Keep these `.excalidraw` files as the source of truth for iterative revisions.

---

**Questions, feedback, or challenges to this methodology?**  
File an issue in this repository or reach out at [support@greatinvert.com](mailto:support@greatinvert.com).

---

*Last updated: March 8, 2026*  
*Methodology: McDonald (2026), adapted by Tim Dickey*  
*Version: 3.0*
