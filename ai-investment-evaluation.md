# AI Investment Evaluation Framework

**Author:** Yash Gaidhani  
**Version:** 1.0  
**Last Updated:** August 2026  
**Sources:** McKinsey AI ROI research (public), Gartner FinOps for AI (public), independent synthesis.

---

Most AI investment cases fail before the pitch even ends because AI product teams speak in technical gains—accuracy, latency, or F1 scores—while the CFO speaks exclusively in capital allocation. 

Driven by tightening macroeconomic conditions, the era of funding AI purely for "innovation" or "experimentation" has ended. Enterprises are racing to secure first-mover advantage before blue oceans turn red, but they are colliding with a harsh reality: AI is inherently probabilistic. Unlike traditional deterministic software, AI cannot guarantee 100% accuracy, creating ambiguity in value realization. 

Furthermore, AI costs do not scale linearly. Moving from a localized pilot to an enterprise rollout creates a "hockey stick" cost curve. Driven by change management overhead, infrastructure scaling, and compounding token consumption, execution costs routinely jump 4x to 5x upon enterprise deployment. When teams fail to model these scaling realities—including a standard ~7% macroeconomic inflation rate on future compute and labor—their day-two operations destroy their day-one business case.

This framework forces AI teams to start with the core business problem, assess organizational data readiness, and translate probabilistic technical outputs into the definitive, risk-adjusted financial metrics required to secure executive approval.

## 1. The Four AI Value Buckets

To gain funding, every AI capability must be mapped to one of these four financial impact categories:

1. **Efficiency and Cost Reduction:** The most measurable and credible bucket. Example: AI-powered ticket triage reducing L1 support volume by 40%, or automated reporting reducing analyst hours by 60%.
2. **Revenue Enhancement:** Harder to prove; requires strict A/B testing and statistical attribution to validate. Examples: Next-best-action personalization, churn prediction, and dynamic pricing optimization.
3. **Risk Mitigation:** Finance teams chronically undervalue this unless it is explicitly quantified. Use actuarial framing: Expected Loss Avoided = (Probability of Event) × (Financial Impact of Event).
4. **Strategic Optionality:** Capabilities that unlock future products or market positions. Frame this using real options theory—what net-new revenue streams does this infrastructure make possible in Year 3?

---

## 2. The Risk-Adjusted ROI Formula

**Standard ROI:**
ROI = (Net Benefit ÷ Total Cost) × 100

**Why standard ROI fails for AI:**
It ignores implementation risk, model drift, and the asymmetric downside of governance failures.

**Risk-Adjusted ROI:**
`Risk-Adjusted ROI = ((Gross Benefit × Risk Multiplier) - Total Cost) ÷ Total Cost × 100`

**Risk Multiplier by Implementation Risk Level:**

| Risk Level | Multiplier | When to Apply |
|---|---|---|
| Low | 1.0 | Proven technology, low regulatory exposure, strong internal capability |
| Medium | 0.75 | New technology category, moderate regulatory exposure, mixed capability |
| High | 0.5 | Unproven technology, high regulatory exposure, low internal capability |

**Total Cost Components (full 3-year TCO):**

| Cost Category | Year 1 | Year 2 | Year 3 |
|---|---|---|---|
| Implementation (build/integrate) | | | |
| Licensing / API costs | | | |
| Infrastructure (compute, storage) | | | |
| Internal team (FTE time allocated) | | | |
| Model retraining and maintenance | | | |
| Governance and compliance overhead | | | |
| Failed PoC write-offs | | | |
| **Total** | | | |

**Payback Period:**
`Payback Period (months) = Total Implementation Cost ÷ Monthly Net Benefit`

**The CFO test:**
If the Risk-Adjusted ROI is below 25% over 3 years, or the payback period exceeds 18 months, expect significant pushback from finance without a strong strategic optionality argument.

---

## 3. Kill, Keep, or Optimise: Portfolio Triage

For enterprises with existing AI pilot portfolios, capital allocation requires ruthlessly culling underperforming models.

* **Kill Criteria:** Monthly P&L impact is zero or negative; the system has fewer than 10 active weekly users; or a vendor has released a commodity duplicate of the capability at a lower TCO.
* **Keep Criteria:** Measured Risk-Adjusted ROI is positive; active daily usage is consistently growing.
* **Optimise Criteria:** The strategic intent remains valid, but the tool is underperforming on ROI due to implementation gaps or poor change management. Initiate a strict 90-day improvement sprint before making a final Kill/Keep decision.

---

## 4. Overcoming Top CFO Objections

1. **"We cannot quantify the benefit."**
   * **Response:** Every AI benefit is quantifiable if you work backward from the business metric it influences. If you cannot identify the specific business metric (e.g., call handling time, cart abandonment rate), the use case is not mature enough for investment.
2. **"The payback period is too long."**
   * **Response:** Shift the focus to Strategic Optionality. Demonstrate what future revenue streams or market position this foundational capability unlocks, proving that the cost of inaction (falling behind competitors) outweighs the immediate capital expenditure.
3. **"What if the model degrades and accuracy drops?"**
   * **Response:** Acknowledge the reality of model drift upfront. Show that continuous drift monitoring, automated retraining pipelines, and human-in-the-loop fallback costs have already been fully modeled into the Year 2 and Year 3 TCO.

---
*This framework synthesises publicly available corporate finance principles and independent analysis. It is not based on any confidential client or employer data.*  
*— Yash Gaidhani | XLRI 2026 | linkedin.com/in/yashgaidhani-xlri*
