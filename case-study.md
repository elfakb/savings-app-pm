# Savings App — A Product Discovery & UX Research Case Study

> Note: This is a simulated / practice case study created for portfolio
> purposes. Interviews, insights, and testing sessions are constructed
> based on realistic behavioral patterns and secondary research on youth
> financial behavior, not live user interviews. This is disclosed
> transparently to demonstrate process and thinking, not to claim real
> field research.

## Overview

Young people want to save money — but most don't. This case study
explores why, and walks through a full product discovery process: from
raw user insight to a validated, iterated product concept.

**Role:** Product Manager / UX Researcher (solo project)
**Scope:** Product discovery, user research, ideation, low-fidelity design, usability testing
**Timeline:** [Add your timeframe, e.g. "3 weeks"]

---

## 1. The Problem Space

Financial apps already exist. Investment platforms already exist. So why
do so many young people still fail to build even basic savings habits?

Rather than starting with a solution, this project started with a
question: **what actually happens in a young person's head when they try
to save money — and where does it break down?**

---

## 2. Research: Simulated Interviews

To explore this, 17 raw insights were synthesized across four realistic
user profiles, each representing a distinct income and life situation:

1. Recent graduate (fixed income)
2. University student (part-time, low/irregular income)
3. Early-career employee (1-2 years, mid income)
4. Freelancer / gig worker (highly irregular income)

Full raw insights: [`01-research/raw-insights.md`](01-research/raw-insights.md)

These insights were then grouped using affinity mapping into six core
pain points:

1. **Lack of Visibility** — users don't know where their money goes
2. **Trust / Complexity** — financial products feel risky and confusing
3. **Perceived Meaninglessness** — small amounts feel not worth saving
4. **Unsustainability** — saving habits break at the first setback
5. **Irregular Income Mismatch** — fixed systems don't work for variable income
6. **Goal Ambiguity** — no concrete reason to save, so motivation fades

Full mapping: [`01-research/affinity-mapping.md`](01-research/affinity-mapping.md)

---

## 3. From Pain Points to Jobs to Be Done

Each pain point was translated into a Job to Be Done (JTBD) — reframing
"users complain about X" into "users are trying to accomplish Y."

Example:
> "When my income changes month to month, I want a flexible saving
> method, so I don't feel excluded by systems built for fixed salaries."

Full JTBD list: [`01-research/jtbd.md`](01-research/jtbd.md)

---

## 4. Personas

Two personas were built to represent the two most distinct behavioral
patterns found in the research — not by demographics, but by income
structure and the resulting saving behavior:

| | Mert Yıldız | Ece Demir |
|---|---|---|
| Income | Fixed | Irregular |
| Core barrier | Complexity, procrastination | Fixed systems don't fit variable income |
| Core need | Visibility + trust | Flexibility + a buffer against uncertainty |

Full personas: [`02-personas/persona-mert.md`](02-personas/persona-mert.md) · [`02-personas/persona-ece.md`](02-personas/persona-ece.md)

---

## 5. Customer Journey Maps

Mapping each persona's emotional journey revealed a **Moment of Truth**
for each:

- **Mert:** The moment he opens the investment/fund tab mid-month — this
  is where he either tries or gives up.
- **Ece:** The moment she realizes, during a low-income month, that she
  has no financial buffer — this is where panic and regret peak.

These moments became the anchor points for the entire product concept.

Full journey maps: [`03-journey-maps/journey-map-mert.md`](03-journey-maps/journey-map-mert.md) · [`03-journey-maps/journey-map-ece.md`](03-journey-maps/journey-map-ece.md)

---

## 6. Problem Statement & How Might We

**Problem Statement:**
> Young individuals aged 18-27 — regardless of whether their income is
> stable or irregular — want to build savings for financial security.
> However, existing financial tools are complex, fail to build trust,
> and don't adapt to different income patterns. This results in savings
> behavior that either never starts or isn't sustained.

From this, persona-specific HMW questions were generated to guide
ideation without jumping straight to a solution.

Full HMWs: [`04-problem-definition/how-might-we.md`](04-problem-definition/how-might-we.md)

---

## 7. Ideation

Using a Crazy 8s approach, 8 divergent ideas were generated, ranging
from round-up savings to social accountability groups. Rather than
picking a single idea, the strongest concept emerged from combining
four of them:

- **Round-Up** savings (solves meaninglessness of small amounts)
- **Income-sensitive percentage** saving (solves irregular income mismatch)
- **Visual goal tracking** (solves visibility + goal ambiguity)
- **"Panic Button"** (solves unsustainability during setbacks)

Full ideation log: [`05-ideation/crazy-8-ideas.md`](05-ideation/crazy-8-ideas.md)

---

## 8. User Flow & Wireframes

The selected concept was mapped into an 8-screen user flow, branching
at the income-type decision (Screen 2) and converging again at a shared
dashboard (Screen 6).

Full user flow: [`06-user-flow/user-flow.md`](06-user-flow/user-flow.md)

Two wireframe formats were produced:
- **Low-fidelity HTML wireframes** (bilingual EN/TR): [`07-wireframes/html/`](07-wireframes/html/)
- **Figma prototype**: [`07-wireframes/figma/figma-link.md`](07-wireframes/figma/figma-link.md)

*(Add wireframe screenshots here once available, e.g.:)*
`![Dashboard wireframe](assets/screenshots/dashboard.png)`

---

## 9. Usability Testing & Iteration

A simulated usability test was run with 5 participants across both
personas, focused on three tasks: setting a goal, understanding the
dashboard, and using the Panic Button.

**Key finding:** The Panic Button — the most novel part of the concept —
initially blended in with routine notifications and was missed by some
participants. This was addressed by increasing its visual distinctiveness
on the alert screen.

Full findings and before/after iteration: [`08-usability-testing/findings-iteration.md`](08-usability-testing/findings-iteration.md)

---

## 10. Reflection & Learnings

- Framing the problem around **behavior**, not just "people don't save
  enough," led to a fundamentally different (and more flexible) product
  concept than a typical "investment app."
- Designing for **two divergent personas** (fixed vs. irregular income)
  early on prevented a one-size-fits-all solution that would have failed
  a large share of users.
- The most valuable product decision — the Panic Button — came directly
  from a Journey Map "Moment of Truth," not from a feature brainstorm in
  isolation. This reinforced how much research should anchor ideation.

## What I'd Do Next
- Run real interviews to validate these simulated insights.
- A/B test the percentage vs. round-up default for new users.
- Explore how the Panic Button could be extended into a broader
  "financial resilience" feature set.

---

## Process Summary

```
Interview → Raw Insights → Affinity Mapping → Pain Points → JTBD →
Persona → Customer Journey Map → Problem Statement → How Might We →
Ideation → User Flow → Wireframe → Usability Test → Iteration
```