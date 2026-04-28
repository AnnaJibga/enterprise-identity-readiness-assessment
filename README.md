# Enterprise Identity Readiness Assessment

*A diagnostic framework for institutional logic articulation, by [Anna Jibgashvili](https://www.linkedin.com/in/annajibgashvili/).*

*Part of the [Foundational Data Products™](https://foundationaldataproducts.com) methodology and the DSIL™ framework.*

---

## What this is

The Enterprise Identity Readiness Assessment is a weighted self-assessment that surfaces whether an enterprise has articulated its institutional logic clearly enough to delegate decisions to AI systems without losing coherence.

It is built on a structural premise: **AI systems do not invent institutional logic. They inherit it.** When the enterprise has not articulated how it makes trade-offs, where decision boundaries sit, what its terms mean, who owns what, and how governance persists — AI systems harden around defaults instead. The result is convergence: every enterprise looks the same, because every enterprise's AI is filling the articulation gap with vendor priors.

This assessment helps leadership see the gap before the AI deployment makes it permanent.

## Who this is for

- Chief Data Officers, Chief AI Officers, Chief Digital Officers
- Chief Risk Officers and Chief Compliance Officers
- Senior data and AI strategy leaders preparing institutional AI deployment
- Transformation leaders in regulated industries (financial services, insurance, healthcare, public sector)
- Board members and senior executives seeking honest baseline on institutional readiness

## How to use it

1. **Download** the Excel template from this repository (`enterprise-identity-readiness-assessment-v1.0.xlsx`).
2. **Score each statement** on a 1–5 scale (1 = Strongly Disagree, 5 = Strongly Agree). Be honest. Self-flattering scores produce useless output.
3. **Read the total weighted score** — calculated automatically. Output is on a 0–100 scale.
4. **Interpret the score** using the bands below.
5. **Act** on the priority gaps. The assessment names the dimensions to address first.

## The six dimensions

The assessment evaluates six dimensions of institutional readiness:

1. **Trade-Off Articulation** — whether the organization can explicitly describe how it prioritizes competing objectives, and whether those trade-offs are documented beyond individual judgment.

2. **Decision Boundary Definition** — whether the organization has documented criteria for what AI should automate versus where human oversight is required, with consistent escalation thresholds.

3. **Institutional Logic Codification** — whether the organization's "way of doing things" is documented in machine-actionable formats, and whether domain concepts have consistent definitions across systems.

4. **Ownership & Accountability Clarity** — whether decision rights and data ownership are explicit enough that AI systems know which authority governs which domain.

5. **Governance Maturity** — whether governance is institutional rather than project-based, and whether mechanisms exist to detect when AI systems drift from institutional intent.

6. **Delegation Preparedness** — whether the organization articulates what success means beyond efficiency metrics before deploying AI in a workflow.

The dimensions are weighted. Trade-Off Articulation, Decision Boundary Definition, and Institutional Logic Codification each carry the highest weight, reflecting that these three are foundational — without them, the others cannot operate. Detailed weighting rationale is in [SCORING_METHODOLOGY.md](./SCORING_METHODOLOGY.md).

## Score interpretation

| Score Range | Band | Diagnosis |
|---|---|---|
| 80–100 | **READY** | Strong institutional identity foundation. Focus on maintaining clarity as AI scales. |
| 60–79 | **PROGRESSING** | Key elements in place, but critical gaps remain. Prioritize trade-off articulation and decision boundaries. |
| 40–59 | **AT RISK** | Significant structural ambiguity. AI delegation without articulation will likely result in convergence. |
| 0–39 | **URGENT** | Institutional logic largely tacit. Immediate action required before AI systems harden around defaults. |

A worked example showing what a completed assessment produces is available in [EXAMPLE_OUTPUT.md](./EXAMPLE_OUTPUT.md).

## Where this sits in the methodology

This assessment is the diagnostic instrument for the first stage of the DSIL™ framework: **Manufacture Context**. Before institutional identity can be stabilized, the enterprise must first see honestly what it has articulated and what remains tacit. This assessment surfaces that picture.

The remaining four DSIL™ stages — Stabilize Identity, Enable Intelligence, Enforce Judgment, and Preserve Intent at Scale — operate on the foundation this assessment helps establish.

For the methodology overview, see [foundationaldataproducts.com](https://foundationaldataproducts.com).

## What this assessment is not

- **Not a technical readiness assessment.** Data quality, infrastructure maturity, and AI tooling readiness are downstream concerns. This assessment is about institutional articulation.
- **Not a benchmark against industry peers.** It is a diagnostic against your own articulation, not a competitive ranking.
- **Not a vendor selection tool.** The output informs whether the organization is ready to deploy AI well, not which AI to deploy.
- **Not a one-time exercise.** Institutional logic shifts. Re-running the assessment annually, or at major strategic inflection points, is recommended.

## Citing this assessment

A formal citation file is provided ([CITATION.cff](./CITATION.cff)). GitHub renders this as a "Cite this repository" button.

Suggested citation:

> Jibgashvili, A. (2026). *Enterprise Identity Readiness Assessment* (v1.0). Foundational Data Products™. https://foundationaldataproducts.com

## License

This work is licensed under [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](./LICENSE).

In plain language: you may share this assessment with attribution. You may not use it for commercial purposes without permission. You may not modify or redistribute modified versions. For commercial licensing or consulting engagement, contact `anna@foundationaldataproducts.com`.

## Canonical references

- **Methodology home:** [foundationaldataproducts.com](https://foundationaldataproducts.com)
- **Methodology writing:** [The Enterprise Identity Imperative on Substack](https://foundationaldataproducts.substack.com)
- **Author:** [Anna Jibgashvili on LinkedIn](https://www.linkedin.com/in/annajibgashvili/)

## Contact

For consultation on digitalizing institutional logic, applying the DSIL™ framework, or commercial licensing of this assessment: `anna@foundationaldataproducts.com`

---

*© 2026 Anna Jibgashvili | Foundational Data Products™ | DSIL™*
