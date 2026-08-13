# Scoring Methodology

*Companion document to the Enterprise Identity Readiness Assessment.*

---

## Purpose

This document explains how the assessment scores work, why the dimensions are weighted as they are, and what each segment of the final score means structurally. It exists because a self-assessment without a transparent scoring methodology is a survey. The scoring is the framework.

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

Trade-Off Articulation measures whether the organization can name how it prioritizes when objectives compete. Every enterprise faces structural trade-offs: speed versus quality, cost versus customer experience, growth versus risk control, short-term efficiency versus long-term capability. Mature institutions name these trade-offs explicitly. Where they are not named, the organization relies on individual judgment, with each leader making the call differently.

When an AI system encounters a conflict between objectives, it follows whatever logic it has been given. Where the organization has not articulated its trade-off logic, the AI inherits the logic of its training data or its vendor, neither of which reflects the organization's competitive positioning.

This dimension carries the highest weight because trade-offs define institutional identity more than any other element. Articulated trade-offs are what allow decisions of consequence to be delegated to AI while the organization's distinctiveness holds.

### 2. Decision Boundary Definition

**Weight per statement: 0.0667 (20.0% of total score across three statements)**

Decision Boundary Definition measures whether the organization has documented criteria for what AI should automate versus what requires human oversight, and whether escalation thresholds are explicit and consistent across similar decision types. Authority boundaries work best when defined architecturally, encoded into systems, rather than stated in policy documents that systems cannot read.

The structural condition this dimension addresses: where boundaries are unstated, AI systems set their own boundaries by inference. Different agents in different parts of the enterprise draw the line differently. Inconsistency at the boundary stays invisible until something fails, at which point redrawing the line is expensive.

This dimension is foundational because every AI deployment decision rests on a boundary judgment. Making those judgments explicit is what makes safe delegation possible.

### 3. Institutional Logic Digitalization

**Weight per statement: 0.0667 (20.0% of total score across three statements)**

Institutional Logic Digitalization measures whether the organization's "way of doing things" is documented in machine-actionable formats rather than prose alone. It also measures whether domain concepts (customer, risk, value, quality) have consistent definitions across systems and teams, and whether strategic intent translates into specific, measurable parameters that systems can honor.

Prose policies do not constrain AI systems. Machine-actionable structure does. An organization with thoughtful written policies and no machine-actionable equivalent has documented its logic for people rather than for the systems that will execute it.

This dimension carries equal weight to Trade-Off Articulation and Decision Boundary Definition because all three are infrastructural. The remaining three dimensions operate on what these establish.

### 4. Ownership & Accountability Clarity

**Weight per statement: 0.05 (15.0% of total score across three statements)**

Ownership & Accountability Clarity measures whether decision rights and data ownership are explicit enough that AI systems can resolve which authority governs which domain. It also measures whether the organization can identify who owns institutional knowledge and who is accountable for its accuracy, and whether knowledge management extends beyond documentation into operational ownership structures.

This dimension is weighted below the foundational three because ownership clarity becomes meaningful once trade-offs, boundaries, and logic are explicit. Owning a clear domain is different from owning an ambiguous one.

### 5. Governance Maturity

**Weight per statement: 0.05 (15.0% of total score across three statements)**

Governance Maturity measures whether the organization's governance is institutional rather than project-based. Mature governance persists beyond individual initiatives and the leaders who sponsored them. Data quality and semantic consistency are enforced systematically rather than case-by-case. Mechanisms exist to detect when AI systems drift from institutional intent.

The structural condition: project-based governance ends when its sponsor moves on. Institutional governance is the difference between a one-time hardening exercise and an enduring capability.

This dimension is weighted equal to Ownership & Accountability Clarity because both build on the foundational three and both are preconditions for the sixth dimension.

### 6. Delegation Preparedness

**Weight per statement: 0.0333 (10.0% of total score across three statements)**

Delegation Preparedness measures whether, before deploying AI in a workflow, the organization articulates what success means beyond efficiency metrics. It also measures whether the organization can distinguish between what should be delegated to AI and what requires human judgment, and whether the AI deployment strategy accounts for institutional coherence rather than technical capability alone.

This dimension carries the lowest weight because it sits downstream of the other five, not because it matters less. An organization scoring well on the foundational dimensions and lower here has the substrate and is building the deployment discipline. An organization scoring well here and lower on the foundational dimensions is deploying AI ahead of the ground it stands on.

The lower weight reflects an asymmetry: foundational gaps show up systemically, delegation gaps show up at project level. Both matter. The foundational gaps reach further.

## Why the weighting is opinionated

The weights are not equal. They are not derived from survey research. They reflect a structural argument about what institutional identity requires.

The foundational three dimensions (Trade-Off Articulation, Decision Boundary Definition, Institutional Logic Digitalization) each carry 20%. Together they account for 60% of the total score. This is intentional. The remaining three perform their function on what these three establish. An organization with strong governance maturity and clear ownership over tacit trade-offs is governing well over ground that has not been defined.

The middle two dimensions (Ownership & Accountability, Governance Maturity) each carry 15%, totaling 30%. They are the operational layer that activates the foundational three.

The final dimension (Delegation Preparedness) carries 10%. It is the deployment-readiness layer, and it operates on what sits upstream of it.

The weighting is what makes this assessment opinionated. An equal-weight version would obscure the structural argument: that institutional identity is built foundation-up rather than feature-by-feature.

## Readiness segment interpretations

The four segments are diagnostic rather than evaluative. Each names a distinct structural condition.

### 80–100: Ready

The organization has substantively articulated its trade-offs, boundaries, and logic. Ownership is clear. Governance is institutional. Delegation discipline exists.

The diagnosis is not that the work is finished. It is that **the foundation is explicit enough for AI deployment to build on rather than fill in.** The work shifts from articulation to maintenance: keeping the foundation current as AI scales, giving new domains and concepts the same articulation treatment, and watching for drift between intent and operation.

What to watch at this segment: institutional logic shifts continuously, so re-assessment keeps the picture honest.

### 60–79: Progressing

Substantive articulation exists in some dimensions and not others. The foundational three are partially explicit with identifiable gaps. Ownership and governance may be ahead of articulation, which is structurally inverted: the organization is governing over logic that varies underneath it.

The diagnosis: **prioritize the foundational three.** Trade-off articulation and decision boundaries are the typical gaps. Closing those lifts the entire score, because the lower-weighted dimensions begin operating on defined ground.

What to watch at this segment: deploying AI now surfaces the gaps publicly. Closing them first, or deploying with the inconsistency named and accepted, are both deliberate choices. Deploying without deciding is not.

### 40–59: Emerging

Foundations are forming. The foundational three are largely tacit. Ownership exists nominally and is not yet actionable for AI. Governance is project-based.

The diagnosis: **how the enterprise articulates its logic from here determines what AI inherits.** Narrow technical work will succeed at this level, such as an isolated forecasting model or a limited classifier. Decisions that depend on institutional logic will be resolved by whatever logic is available, which means vendor priors fill the gap and the organization's distinctive logic gives way over time.

What to watch at this segment: pressure to deploy quickly. Articulation work moves slower than deployment, and deployment ahead of articulation produces an AI implementation structurally indistinguishable from competitors.

### 0–39: Foundational

Institutional logic is largely tacit. Trade-offs are made differently by different leaders. Decision boundaries are inferred. Domain concepts have varying definitions across systems. Ownership is informal. Governance is reactive.

The diagnosis: **this is the moment to author institutional logic explicitly, before AI systems settle around defaults.** Once an AI system has been deployed and integrated into operational workflows, retrofitting institutional articulation is structurally difficult. The organization's logic begins to be defined by the AI's defaults rather than by leadership.

The path forward is articulation before delegation. The order is what matters, and starting here is the highest-value work available.

## What this assessment does not measure

To be explicit about scope:

- **Technical AI readiness.** Model capability, infrastructure, MLOps, AI tool selection. Downstream concerns.
- **Data quality readiness.** Accuracy, completeness, lineage, master data management. These matter and have their own assessments. This one is upstream of those.
- **Workforce AI literacy.** Training, change management, adoption capacity. Important, separately measured.
- **Vendor and platform readiness.** Cloud, security, compliance certifications. Separately measured.
- **Specific use-case readiness.** Whether the organization is ready to deploy a particular AI capability in a particular workflow. Separately scoped.

This assessment measures one thing: whether the institutional logic is articulated clearly enough for AI to execute it without loss of fidelity.

## How to use the score

The total score is a starting point rather than an endpoint. The more useful output is the dimension-level breakdown, and which specific dimensions scored low.

A median score with strong Trade-Off Articulation and weaker Governance Maturity is a different problem from the same median score with weaker Trade-Off Articulation and strong Governance Maturity. The first organization is governing over articulated trade-offs and has yet to make its standards persist. The second is governing consistently over logic that has not been defined.

Treat the score as the diagnosis. Treat the dimension breakdown as the prescription.

---

*© 2026 Anna Jibgashvili | Foundeon | DSIL™*
