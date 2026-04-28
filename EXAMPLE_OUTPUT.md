# Example Output

*A fully completed sample assessment, demonstrating what running the Enterprise Identity Readiness Assessment produces.*

---

## Context for the example

The organization in this example is a fictional mid-size financial services firm preparing to deploy AI agents in customer-facing workflows (account servicing, claim triage, advisor support). Leadership has commissioned the assessment to baseline institutional readiness before approving the AI deployment program. The fictional firm is composite — it is not based on any real organization, and any resemblance to actual enterprises is incidental.

The scores below reflect a realistic mix: the firm has done meaningful work on governance and ownership but has weaker articulation in the foundational dimensions. The total falls in the AT RISK band.

## Completed assessment

### Dimension 1: Trade-Off Articulation

| Statement | Score | Weight | Weighted Score |
|---|---|---|---|
| Our organization can explicitly describe how we prioritize competing objectives (e.g., speed vs. quality, cost vs. customer experience) | 2 | 0.0667 | 2.67 |
| When AI systems face conflicting priorities, we have documented decision hierarchies that reflect institutional values | 1 | 0.0667 | 1.33 |
| Trade-offs that define our competitive positioning are formalized beyond individual judgment | 2 | 0.0667 | 2.67 |
| **Dimension subtotal** | | | **6.67 / 20.00** |

### Dimension 2: Decision Boundary Definition

| Statement | Score | Weight | Weighted Score |
|---|---|---|---|
| We have clear, documented criteria for when decisions should be automated vs. require human oversight | 3 | 0.0667 | 4.00 |
| Escalation thresholds are explicit and consistent across similar decision types | 2 | 0.0667 | 2.67 |
| Authority boundaries for AI systems are defined architecturally, not just in policy documents | 2 | 0.0667 | 2.67 |
| **Dimension subtotal** | | | **9.34 / 20.00** |

### Dimension 3: Institutional Logic Codification

| Statement | Score | Weight | Weighted Score |
|---|---|---|---|
| Our institutional 'way of doing things' is documented in machine-actionable formats, not just prose | 2 | 0.0667 | 2.67 |
| Domain concepts (customer, risk, value, quality) have consistent definitions across systems and teams | 2 | 0.0667 | 2.67 |
| Strategic intent translates into specific, measurable parameters that systems can honor | 1 | 0.0667 | 1.33 |
| **Dimension subtotal** | | | **6.67 / 20.00** |

### Dimension 4: Ownership & Accountability Clarity

| Statement | Score | Weight | Weighted Score |
|---|---|---|---|
| Decision rights and data ownership are explicit enough that AI systems know which authority governs which domain | 3 | 0.05 | 3.00 |
| When institutional knowledge exists, we can identify who owns it and who is accountable for its accuracy | 4 | 0.05 | 4.00 |
| Knowledge management extends beyond documentation to operational ownership structures | 3 | 0.05 | 3.00 |
| **Dimension subtotal** | | | **10.00 / 15.00** |

### Dimension 5: Governance Maturity

| Statement | Score | Weight | Weighted Score |
|---|---|---|---|
| Our governance is institutional rather than project-based (standards persist beyond individual initiatives) | 4 | 0.05 | 4.00 |
| Data quality and semantic consistency are enforced systematically, not case-by-case | 3 | 0.05 | 3.00 |
| We have mechanisms to detect when AI systems drift from institutional intent | 2 | 0.05 | 2.00 |
| **Dimension subtotal** | | | **9.00 / 15.00** |

### Dimension 6: Delegation Preparedness

| Statement | Score | Weight | Weighted Score |
|---|---|---|---|
| Before deploying AI in a workflow, we articulate what success means beyond efficiency metrics | 2 | 0.0333 | 1.33 |
| We can distinguish between what should be delegated to AI and what requires human judgment | 3 | 0.0333 | 2.00 |
| Our AI deployment strategy accounts for institutional coherence, not just technical capability | 2 | 0.0333 | 1.33 |
| **Dimension subtotal** | | | **4.66 / 10.00** |

## Total

| | Score |
|---|---|
| **Total Readiness Score** | **46.34 / 100** |
| **Band** | **AT RISK** |

## Interpretation

### What the total score means

A score of 46.34 places the firm in the AT RISK band. The structural diagnosis: significant institutional ambiguity in the foundational three dimensions. AI delegation at this readiness level will not fail technically — narrow capabilities will function. It will fail structurally. AI will fill articulation gaps with vendor priors, and the firm's distinctive institutional logic will begin to erode as the AI scales.

### Where the gaps are

The dimension-level breakdown tells the structural story more clearly than the total:

- **Trade-Off Articulation: 6.67 / 20.00 (33%).** The firm cannot articulate how it prioritizes competing objectives. AI systems facing trade-offs in this firm will resolve them by defaulting to the priorities embedded in their training data and vendor logic.

- **Institutional Logic Codification: 6.67 / 20.00 (33%).** Domain concepts are inconsistent across systems. Strategic intent does not translate into machine-honored parameters. AI cannot execute logic the firm has not codified.

- **Decision Boundary Definition: 9.34 / 20.00 (47%).** Better than Trade-Off and Logic, but still well below adequate. Documentation exists but architectural enforcement is weak.

- **Delegation Preparedness: 4.66 / 10.00 (47%).** The firm is not articulating what success means before deployment. Without that articulation, success will be defined by the metrics the AI happens to surface.

The strongest dimensions are Ownership & Accountability (10.00 / 15.00, 67%) and Governance Maturity (9.00 / 15.00, 60%). This pattern is structurally backwards. The firm has done the operational layer work without the foundational articulation work. The result is governance imposed on top of inconsistent logic — a configuration that produces inconsistent enforcement, not consistent ones.

### What to act on

The diagnostic prescribes a sequence:

1. **Close the Institutional Logic Codification gap first.** Until domain concepts have consistent definitions, no other dimension can produce reliable output. Customer, risk, value, and quality must be canonically defined and enforced in machine-actionable form.

2. **Codify the trade-offs.** Identify the structural trade-offs that define the firm's competitive positioning (in financial services this typically includes: risk appetite vs. growth, customer experience vs. compliance friction, channel cost vs. relationship depth). Make these trade-offs explicit. Document the priority orderings.

3. **Architect the decision boundaries.** Move boundary definitions from policy documents into architectural enforcement. Where a boundary exists in policy, it must exist in system behavior.

4. **Defer broad AI deployment until the foundational three dimensions reach 60% or higher.** Narrow technical AI deployments may proceed where they do not depend on institutional logic. Customer-facing AI agents and decision-supporting AI should wait.

### What not to do

- Do not deploy AI broadly to "build muscle memory" or "let the team learn." Deploying AI on a weak articulation foundation accelerates the convergence problem. The team learns to operate around AI defaults, which then become institutional defaults.

- Do not address the gaps by hiring more governance staff. The firm already scores well on governance maturity. The gap is upstream.

- Do not treat this as a one-time exercise. Re-assess after the foundational work to confirm progress before committing to broader deployment.

### Re-assessment cadence

The firm should re-run the assessment annually at minimum. More aggressive cadence is recommended during active foundational work (every six months) and at any major strategic inflection point (CEO transition, M&A, regulatory shift).

---

## How to read your own results

The example above shows what a complete output looks like. When you run the assessment on your own organization:

1. **Look at the total score** to understand your band.
2. **Look at dimension-level scores** to understand the structural shape — which dimensions are leading, which are lagging.
3. **Look for the inverse pattern** — strong governance and ownership without strong foundational articulation. This pattern is common and typically the most actionable.
4. **Identify the lowest-scoring foundational dimension.** That is your starting point. The total score will not improve durably until the lowest foundational dimension does.

For consultation on interpreting results or developing an articulation roadmap, contact `anna@foundationaldataproducts.com`.

---

*© 2026 Anna Jibgashvili | Foundational Data Products™ | DSIL™*
