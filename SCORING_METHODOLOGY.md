# Scoring Methodology

*Companion document to the Enterprise Identity Readiness Assessment.*

---

## Purpose

This document explains how the assessment scores work, why the dimensions are weighted as they are, and what each band of the final score actually means structurally. It exists because a self-assessment without a transparent scoring methodology is just a survey. The scoring is the framework.

## Structure

The assessment evaluates six dimensions through eighteen statements (three statements per dimension). Each statement is scored 1–5 on a Likert agreement scale. Each statement carries a weight. The total score is calculated on a 0–100 scale.

The formula for each weighted score is:

```
Weighted Score = IF(Score is blank, blank, Score × Weight × 20)
```

The multiplier of 20 normalizes a 1–5 scale across weights summing to 1.0 onto a 0–100 output range. A perfect score (all 5s across all weighted dimensions) produces 100 points.

## The dimensions, in depth

### 1. Trade-Off Articulation

**Weight per statement: 0.0667 (20.0% of total score across three statements)**

Trade-Off Articulation measures whether the organization can name how it prioritizes when objectives compete. Every enterprise faces structural trade-offs: speed versus quality, cost versus customer experience, growth versus risk control, short-term efficiency versus long-term capability. Mature institutions name these trade-offs explicitly. Immature institutions rely on individual judgment, with each leader making the call differently and inconsistently.

When an AI system encounters a conflict between objectives, it follows whatever logic it has been given. If the organization has not articulated its trade-off logic, the AI inherits the logic of its training data or its vendor — neither of which reflects the organization's competitive positioning.

This dimension carries the highest weight because trade-offs define institutional identity more than any other element. An organization without articulated trade-offs cannot delegate any decision of consequence to AI without losing its distinctiveness.

### 2. Decision Boundary Definition

**Weight per statement: 0.0667 (20.0% of total score across three statements)**

Decision Boundary Definition measures whether the organization has documented criteria for what AI should automate versus what requires human oversight, and whether escalation thresholds are explicit and consistent across similar decision types. Authority boundaries should be defined architecturally — encoded into systems — not just stated in policy documents that systems cannot read.

The structural risk this dimension addresses: when boundaries are unstated, AI systems set their own boundaries by inference. Different agents in different parts of the enterprise will draw the line differently. Inconsistency at the boundary is invisible until something fails, at which point it is too late to redraw the line.

This dimension is foundational because every AI deployment decision implicitly rests on a boundary judgment. Making those judgments explicit is a precondition for safe delegation.

### 3. Institutional Logic Codification

**Weight per statement: 0.0667 (20.0% of total score across three statements)**

Institutional Logic Codification measures whether the organization's "way of doing things" is documented in machine-actionable formats — not just prose. It also measures whether domain concepts (customer, risk, value, quality) have consistent definitions across systems and teams, and whether strategic intent translates into specific, measurable parameters that systems can honor.

Prose policies cannot constrain AI systems. Only machine-actionable structure can. An organization that has thoughtful written policies but no machine-actionable equivalent has documented its logic for humans, not for the systems that will execute it.

This dimension carries equal weight to Trade-Off Articulation and Decision Boundary Definition because all three are infrastructural. Without them, the remaining three dimensions cannot operate well.

### 4. Ownership & Accountability Clarity

**Weight per statement: 0.05 (15.0% of total score across three statements)**

Ownership & Accountability Clarity measures whether decision rights and data ownership are explicit enough that AI systems can resolve which authority governs which domain. It also measures whether the organization can identify who owns institutional knowledge and who is accountable for its accuracy, and whether knowledge management extends beyond documentation into operational ownership structures.

This dimension is weighted slightly below the foundational three because ownership clarity becomes meaningful only after trade-offs, boundaries, and logic are codified. Owning ambiguity is not the same as owning a clear domain.

### 5. Governance Maturity

**Weight per statement: 0.05 (15.0% of total score across three statements)**

Governance Maturity measures whether the organization's governance is institutional rather than project-based. Mature governance persists beyond individual initiatives and the leaders who sponsored them. Data quality and semantic consistency are enforced systematically, not case-by-case. Mechanisms exist to detect when AI systems drift from institutional intent.

The structural risk: project-based governance dies when its sponsor moves on. Institutional governance is the difference between a one-time hardening exercise and an enduring capability.

This dimension is weighted equal to Ownership & Accountability Clarity because both depend on the foundational three but are themselves preconditions for the sixth dimension.

### 6. Delegation Preparedness

**Weight per statement: 0.0333 (10.0% of total score across three statements)**

Delegation Preparedness measures whether, before deploying AI in a workflow, the organization articulates what success means beyond efficiency metrics. It also measures whether the organization can distinguish between what should be delegated to AI and what requires human judgment, and whether the AI deployment strategy accounts for institutional coherence rather than just technical capability.

This dimension carries the lowest weight not because it is unimportant — it is critical — but because it is downstream of the other five. An organization that scores well on the foundational dimensions but poorly here has the substrate but lacks the deployment discipline. An organization that scores well here but poorly on the foundational dimensions is deploying AI on quicksand.

The lower weight reflects the asymmetry: foundational gaps cause systemic failure; delegation gaps cause project-level failure. Both matter; the foundational gaps matter more.

## Why the weighting is opinionated

The weights are not equal. They are not derived from survey research. They reflect a structural argument about what institutional identity requires.

The foundational three dimensions (Trade-Off Articulation, Decision Boundary Definition, Institutional Logic Codification) each carry 20%. Together, they account for 60% of the total score. This is intentional. Without these three, the remaining three cannot perform their function. An organization with strong governance maturity and clear ownership but tacit trade-offs is governing well over a vacuum.

The middle two dimensions (Ownership & Accountability, Governance Maturity) each carry 15%, totaling 30%. They are the operational layer that activates the foundational three.

The final dimension (Delegation Preparedness) carries 10%. It is the deployment-readiness layer. It cannot compensate for upstream gaps.

The weighting is what makes this assessment opinionated. A balanced equal-weight version would obscure the structural argument: that institutional identity is built foundation-up, not feature-by-feature.

## Score band interpretations

The four bands are diagnostic, not evaluative. Each band names a distinct structural condition.

### 80–100: READY

The organization has substantively articulated its trade-offs, boundaries, and logic. Ownership is clear. Governance is institutional. Delegation discipline exists.

The diagnosis is not "you are done." It is: **you have built a foundation that AI deployment will not erode.** The work shifts from articulation to maintenance — keeping the foundation honest as AI scales, ensuring new domains and concepts get the same articulation treatment, watching for drift between intent and operation.

Risk at this band: complacency. Organizations that score in Ready sometimes assume they are durably ready. Institutional logic shifts continuously. Re-assessment is essential.

### 60–79: PROGRESSING

Substantive articulation exists in some dimensions but not all. The foundational three are likely partially codified but with gaps. Ownership and governance may be ahead of articulation, which is structurally backwards — the organization is governing inconsistently because the underlying logic is uneven.

The diagnosis: **prioritize the foundational three.** Trade-off articulation and decision boundaries are the typical gaps. Closing those gaps lifts the entire score because the lower-weighted dimensions begin to operate on solid ground.

Risk at this band: deploying AI now will surface the gaps publicly. Either close the gaps first or accept that AI deployment will reveal the inconsistency.

### 40–59: AT RISK

Significant structural ambiguity. The foundational three are largely tacit. Ownership exists nominally but is not actionable for AI. Governance is project-based.

The diagnosis: **AI delegation at this readiness level will not succeed structurally.** It may succeed at narrow technical tasks (an isolated forecasting model, a limited classifier). It will fail when AI is asked to make decisions that depend on institutional logic the organization has not articulated. The result is convergence — the AI fills the gap with vendor priors, and the organization's distinctive logic erodes.

Risk at this band: pressure to deploy AI quickly. The pressure is the problem. Articulation work is slower than deployment, but deployment without articulation produces an AI implementation that is structurally indistinguishable from competitors.

### 0–39: URGENT

Institutional logic is largely tacit. Trade-offs are made differently by different leaders. Decision boundaries are inferred. Domain concepts have inconsistent definitions across systems. Ownership is informal. Governance is reactive.

The diagnosis: **AI systems harden around defaults at this readiness level, and the defaults become permanent.** Once an AI system has been deployed and integrated into operational workflows, it becomes structurally difficult to retrofit institutional articulation. The organization's logic begins to be defined by the AI's defaults rather than by leadership.

Risk at this band: existential, not project-level. Without articulation, the organization risks losing its institutional distinctiveness as AI scales.

The path forward is not "deploy AI more cautiously." It is "articulate before delegating." The order matters.

## What this assessment does not measure

To be explicit about scope:

- **Technical AI readiness** — model capability, infrastructure, MLOps, AI tool selection. These are downstream concerns.
- **Data quality readiness** — accuracy, completeness, lineage, master data management. These matter, and they have their own assessments. This one is upstream of those.
- **Workforce AI literacy** — training, change management, adoption capacity. Important, separately measured.
- **Vendor and platform readiness** — cloud, security, compliance certifications. Separately measured.
- **Specific use-case readiness** — whether the organization is ready to deploy a particular AI capability in a particular workflow. Separately scoped.

This assessment measures one specific thing: whether the institutional logic is articulated clearly enough for AI to execute it without loss of fidelity.

## How to use the score

The total score is a starting point, not an endpoint. The more useful output is the dimension-level breakdown — which specific dimensions scored low.

A median score with strong Trade-Off Articulation and weak Governance Maturity is a different problem than the same median score with weak Trade-Off Articulation and strong Governance Maturity. The first organization is governing well over articulated trade-offs but cannot persist its standards. The second is governing consistently over a vacuum.

Treat the score as the diagnosis. Treat the dimension breakdown as the prescription.

---

*© 2026 Anna Jibgashvili | Foundational Data Products™ | DSIL™*
