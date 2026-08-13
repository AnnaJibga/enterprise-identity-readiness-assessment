# Enterprise Identity Readiness Assessment

*A diagnostic framework for institutional logic articulation, by [Anna Jibgashvili](https://www.linkedin.com/in/annajibgashvili/).*

*Part of the [Foundeon](https://foundeon.com) methodology and the DSIL™ framework.*

---

## What this is

The Enterprise Identity Readiness Assessment is a weighted self-assessment that surfaces whether an enterprise has articulated its institutional logic clearly enough to delegate decisions to AI systems without losing coherence.

It is built on a structural premise: **AI systems do not invent institutional logic. They inherit it.** Where the enterprise has not articulated how it makes trade-offs, where decision boundaries sit, what its terms mean, who owns what, and how governance persists, AI systems settle around defaults instead. The result is convergence: every enterprise looks the same, because every enterprise's AI is filling the articulation gap with vendor priors.

This assessment helps leadership see the gap while it is still open to change.

## Who this is for

- Chief Data Officers, Chief AI Officers, Chief Digital Officers
- Chief Risk Officers and Chief Compliance Officers
- Senior data and AI strategy leaders preparing institutional AI deployment
- Transformation leaders in regulated industries (financial services, insurance, healthcare, public sector)
- Board members and senior executives seeking an honest baseline on institutional readiness

## How to use it

1. **Download** the Excel template from this repository (`enterprise-identity-readiness-assessment-v1.0.xlsx`).
2. **Score each statement** on a 1–5 scale (1 = Strongly Disagree, 5 = Strongly Agree). Rate each statement against your current-state evidence, not your target-state ambition. Self-flattering scores produce useless output.
3. **Read the total weighted score**, calculated automatically. Output is on a 0–100 scale.
4. **Interpret the score** using the segments below.
5. **Act** on the priority gaps. The assessment names the dimensions to address first.

An interactive version is available at [foundeon.com/eira](https://foundeon.com/eira).

## The six dimensions

The assessment evaluates six dimensions of institutional readiness:

1. **Trade-Off Articulation.** Whether the organization can explicitly describe how it prioritizes competing objectives, and whether those trade-offs are documented beyond individual judgment.

2. **Decision Boundary Definition.** Whether the organization has documented criteria for what AI should automate versus where human oversight is required, with consistent escalation thresholds.

3. **Institutional Logic Digitalization.** Whether the organization's "way of doing things" is documented in machine-actionable formats, and whether domain concepts have consistent definitions across systems.

4. **Ownership & Accountability Clarity.** Whether decision rights and data ownership are explicit enough that AI systems know which authority governs which domain.

5. **Governance Maturity.** Whether governance is institutional rather than project-based, and whether mechanisms exist to detect when AI systems drift from institutional intent.

6. **Delegation Preparedness.** Whether the organization articulates what success means beyond efficiency metrics before deploying AI in a workflow.

The dimensions are weighted. Trade-Off Articulation, Decision Boundary Definition, and Institutional Logic Digitalization each carry the highest weight, reflecting that these three are foundational, and the others operate on what they establish. Detailed weighting rationale is in [SCORING_METHODOLOGY.md](./SCORING_METHODOLOGY.md).

## Readiness segments

| Score Range | Segment | What it means |
| ----------- | ------- | ------------- |
| 80–100 | **Ready** | Institutional logic is articulated clearly enough to delegate decisions to AI. The work ahead is maintaining that clarity as AI scales. |
| 60–79 | **Progressing** | Key elements are in place. Trade-off articulation and decision boundaries are where the remaining gaps close fastest. |
| 40–59 | **Emerging** | Foundations are forming. How the enterprise articulates trade-offs, decision boundaries, and institutional logic will determine what AI inherits. |
| 0–39 | **Foundational** | The work starts at the foundation. Making institutional logic explicit is the highest-value next step before AI systems settle into defaults. |

A worked example showing what a completed assessment produces is available in [EXAMPLE_OUTPUT.md](./EXAMPLE_OUTPUT.md).

## Where this sits in the methodology

This assessment is the diagnostic entry point to the DSIL™ framework. Digital Substrate Identity Layer / DSIL™ is Foundeon's proprietary method for making enterprise meaning, policy context, decision rights, governance expectations, and accountability explicit before AI systems consume them.

Before that substrate can be defined, the enterprise needs an honest view of what it has already articulated and what remains tacit. This assessment produces that view.

For the methodology overview, see [foundeon.com](https://foundeon.com).

## What this assessment is not

- **Not a technical readiness assessment.** Data quality, infrastructure maturity, and AI tooling readiness are downstream concerns. This assessment is about institutional articulation.
- **Not a benchmark against industry peers.** It is a diagnostic against your own articulation, not a competitive ranking.
- **Not a vendor selection tool.** The output informs whether the organization is ready to deploy AI well, not which AI to deploy.
- **Not a one-time exercise.** Institutional logic shifts. Re-running the assessment annually, or at major strategic inflection points, is recommended.

## Citing this assessment

A formal citation file is provided ([CITATION.cff](./CITATION.cff)). GitHub renders this as a "Cite this repository" button.

Suggested citation:
> Jibgashvili, A. (2026). *Enterprise Identity Readiness Assessment* (v1.1). Foundeon. <https://foundeon.com>

## License

This work is licensed under [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](./LICENSE.md).

In plain language: you may share this assessment with attribution. You may not use it for commercial purposes without permission. You may not modify or redistribute modified versions. For commercial licensing or consulting engagement, contact `anna@foundeon.com`.

## Canonical references

- **Methodology home:** [foundeon.com](https://foundeon.com)
- **Interactive assessment:** [foundeon.com/eira](https://foundeon.com/eira)
- **Methodology writing:** [The Enterprise Identity Imperative on Substack](https://foundationaldataproducts.substack.com)
- **Author:** [Anna Jibgashvili on LinkedIn](https://www.linkedin.com/in/annajibgashvili/)

## Related Foundeon frameworks

The Enterprise Identity Readiness Assessment (EIRA) is used as the readiness input for the Workflow Disposition Framework (WDF™).

WDF™ sequences AI-candidate workflows into Manual, Hybrid, or Automated dispositions based on impact, consequence, and the lowest relevant EIRA readiness dimension.

Related repository: <https://github.com/AnnaJibga/workflow-disposition-framework>

## Contact

For consultation on digitalizing institutional logic, applying the DSIL™ framework, or commercial licensing of this assessment: `anna@foundeon.com`

---

*© 2026 Anna Jibgashvili | Foundeon | DSIL™*
