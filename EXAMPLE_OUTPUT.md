# Example Output

*A fully completed sample assessment, demonstrating what running the Enterprise Identity Readiness Assessment produces.*

---

## Context for the example

The organization in this example is a fictional mid-size financial services firm preparing to deploy AI agents in customer-facing workflows (account servicing, claim triage, advisor support). Leadership has commissioned the assessment to baseline institutional readiness before approving the AI deployment program. The fictional firm is composite. It is not based on any real organization, and any resemblance to actual enterprises is incidental.

The scores below reflect a realistic mix: the firm has done meaningful work on governance and ownership, with weaker articulation in the foundational dimensions. The total falls in the Emerging segment.

## Completed assessment

### Dimension 1: Trade-Off Articulation

| Statement | Score | Weight | Weighted Score |
| --- | --- | --- | --- |
| Our organization can explicitly describe how we prioritize competing objectives (e.g., speed vs. quality, cost vs. customer experience) | 2 | 0.0667 | 2.67 |
| When AI systems face conflicting priorities, we have documented decision hierarchies that reflect institutional values | 1 | 0.0667 | 1.33 |
| Trade-offs that define our competitive positioning are formalized beyond individual judgment | 2 | 0.0667 | 2.67 |
| **Dimension subtotal** | | | **6.67 / 20.00** |

### Dimension 2: Decision Boundary Definition

| Statement | Score | Weight | Weighted Score |
| --- | --- | --- | --- |
| We have clear, documented criteria for when decisions should be automated vs. require human oversight | 3 | 0.0667 | 4.00 |
| Escalation thresholds are explicit and consistent across similar decision types | 2 | 0.0667 | 2.67 |
| Authority boundaries for AI systems are defined architecturally, not just in policy documents | 2 | 0.0667 | 2.67 |
| **Dimension subtotal** | | | **9.34 / 20.00** |

### Dimension 3: Institutional Logic Digitalization

| Statement | Score | Weight | Weighted Score |
| --- | --- | --- | --- |
| Our institutional 'way of doing things' is documented in machine-actionable formats, not just prose | 2 | 0.0667 | 2.67 |
| Domain concepts (customer, risk, value, quality) have consistent definitions across systems and teams | 2 | 0.0667 | 2.67 |
| Strategic intent translates into specific, measurable parameters that systems can honor | 1 | 0.0667 | 1.33 |
| **Dimension subtotal** | | | **6.67 / 20.00** |

### Dimension 4: Ownership & Accountability Clarity

| Statement | Score | Weight | Weighted Score |
| --- | --- | --- | --- |
| Decision rights and data ownership are explicit enough that AI systems know which authority governs which domain | 3 | 0.05 | 3.00 |
| When institutional knowledge exists, we can identify who owns it and who is accountable for its accuracy | 4 | 0.05 | 4.00 |
| Knowledge management extends beyond documentation to operational ownership structures | 3 | 0.05 | 3.00 |
| **Dimension subtotal** | | | **10.00 / 15.00** |

### Dimension 5: Governance Maturity

| Statement | Score | Weight | Weighted Score |
| --- | --- | --- | --- |
| Our governance is institutional rather than project-based (standards persist beyond individual initiatives) | 4 | 0.05 | 4.00 |
| Data quality and semantic consistency are enforced systematically, not case-by-case | 3 | 0.05 | 3.00 |
| We have mechanisms to detect when AI systems drift from institutional intent | 2 | 0.05 | 2.00 |
| **Dimension subtotal** | | | **9.00 / 15.00** |

### Dimension 6: Delegation Preparedness

| Statement | Score | Weight | Weighted Score |
| --- | --- | --- | --- |
| Before deploying AI in a workflow, we articulate what success means beyond efficiency metrics | 2 | 0.0333 | 1.33 |
| We can distinguish between what should be delegated to AI and what requires human judgment | 3 | 0.0333 | 2.00 |
| Our AI deployment strategy accounts for institutional coherence, not just technical capability | 2 | 0.0333 | 1.33 |
| **Dimension subtotal** | | | **4.66 / 10.00** |

## Total

| | Score |
| --- | --- |
| **Total Readiness Score** | **46.34 / 100** |
| **Segment** | **Emerging** |

## Interpretation

### What the total score means

A score of 46.34 places the firm in the Emerging segment. Foundations are forming, and the articulation work in the foundational three dimensions is what determines what AI inherits. At this readiness level, narrow AI capabilities will function technically. The structural question is different: where articulation is thin, AI fills the gap with vendor priors, and the firm's distinctive institutional logic gradually gives way to defaults as AI scales.

### Where the gaps are

The dimension-level breakdown tells the structural story more clearly than the total:

- **Trade-Off Articulation: 6.67 / 20.00 (33%).** How the firm prioritizes competing objectives is not yet articulated. AI systems facing trade-offs will resolve them against the priorities embedded in their training data and vendor logic until the firm's own priorities are explicit.

- **Institutional Logic Digitalization: 6.67 / 20.00 (33%).** Domain concepts vary across systems, and strategic intent does not yet translate into machine-honored parameters. AI executes the logic the firm has made explicit.

- **Decision Boundary Definition: 9.34 / 20.00 (47%).** Stronger than the two above. Documentation exists; architectural enforcement is where the remaining work sits.

- **Delegation Preparedness: 4.66 / 10.00 (47%).** Success is not yet defined before deployment. Where it is left open, it will be defined by whichever metrics the AI surfaces.

The strongest dimensions are Ownership & Accountability (10.00 / 15.00, 67%) and Governance Maturity (9.00 / 15.00, 60%). This pattern is structurally inverted, and it is common. The firm has built the operational layer ahead of the foundational articulation beneath it, which produces governance applied over varying logic, and therefore uneven enforcement rather than consistent enforcement.

### What to act on

The diagnostic prescribes a sequence:

1. **Close the Institutional Logic Digitalization gap first.** Consistent domain definitions are what every other dimension depends on. Customer, risk, value, and quality are canonically defined and enforced in machine-actionable form.

2. **Make the trade-offs explicit.** Identify the structural trade-offs that define the firm's competitive positioning. In financial services this typically includes risk appetite against growth, customer experience against compliance friction, and channel cost against relationship depth. Document the priority orderings.

3. **Architect the decision boundaries.** Move boundary definitions from policy documents into architectural enforcement. Where a boundary exists in policy, it should exist in system behavior.

4. **Sequence broad AI deployment behind the foundational three dimensions reaching 60% or higher.** Narrow technical deployments may proceed where they do not depend on institutional logic. Customer-facing AI agents and decision-supporting AI benefit from waiting.

### What to be deliberate about

- Deploying AI broadly to build familiarity accelerates the convergence problem. Teams learn to operate around AI defaults, and those defaults become institutional.

- Additional governance staff will not close these gaps. The firm already scores well on governance maturity. The work is upstream of it.

- Re-assessment after the foundational work confirms progress before broader deployment is committed.

### Re-assessment cadence

The firm should re-run the assessment annually at minimum. A more frequent cadence is useful during active foundational work (every six months) and at any major strategic inflection point (CEO transition, M&A, regulatory shift).

---

## How to read your own results

The example above shows what a complete output looks like. When you run the assessment on your own organization:

1. **Look at the total score** to understand your segment.
2. **Look at dimension-level scores** to understand the structural shape: which dimensions are leading, which are lagging.
3. **Look for the inverted pattern.** Strong governance and ownership without strong foundational articulation is common, and typically the most actionable finding.
4. **Identify the lowest-scoring foundational dimension.** That is the starting point. The total score improves durably once the lowest foundational dimension does.

For consultation on interpreting results or developing an articulation roadmap, contact `anna@foundeon.com`.

---

*© 2026 Anna Jibgashvili | Foundeon | DSIL™*
