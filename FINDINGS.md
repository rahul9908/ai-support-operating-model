# Pilot Evaluation Findings

## Management interpretation

The illustrative four-week pilot shows a promising but unfinished operating model. The system is already strong enough to assist agents with classification: accuracy reached **91.5%**, above the 90% pilot gate. Handling time also moved from a 12-minute baseline to **9.175 minutes**, a reduction of about **23.5%**. That is meaningful capacity improvement, but the workbook correctly treats it as capacity value rather than guaranteed cash savings.

The principal control gap concerns response safety. The unsupported-claim rate fell from 6.0% to **2.2%**, yet the release rule requires less than 2%. The result indicates that generated responses still require additional verification before customer delivery. Response acceptance is **52%**, below the 55% target, which reinforces the need to improve retrieval quality, citation visibility, and drafting prompts before expanding the pilot.

Customer experience is encouraging. Satisfaction reached **4.24/5**, above the 4.2 threshold, while first-contact resolution reached **72%**. Escalation is **26%**, below the 30% planning target. That lower rate is not automatically a success: the team must confirm that sensitive cases are still being captured at 100% before interpreting fewer escalations as efficiency.

## Decision implication

The evidence supports **continued controlled pilot operation**, not unrestricted rollout. Keep human approval mandatory, focus the next improvement cycle on grounded answers and response acceptance, and repeat the release sample until the unsupported-claim gate is met for four consecutive weeks. This is a stronger recommendation than calling the pilot a simple “success” because it separates what is working from what still creates customer and compliance risk.

## Data-quality and interpretation notes

- All values are illustrative planning data from the workbook and are not production claims.
- The dashboard labels each measure as Met, Below, or Within against an explicit baseline and target.
- Cost per resolution improved from $7.10 to $6.10, but the business case distinguishes modeled capacity value from committed savings.
- The pilot expansion rule requires four consecutive weeks meeting all gates, so one favorable snapshot cannot authorize scale.
- High-risk capture, hallucination review, and subgroup performance should be checked in the evaluation workbook before any production decision.

![AI Support Pilot Dashboard](docs/assets/ai-support-pilot-dashboard.png)

*Figure 1. Illustrative dashboard snapshot. The visual makes the trade-off visible: classification and satisfaction are on track, while unsupported claims and response acceptance still require work.*
