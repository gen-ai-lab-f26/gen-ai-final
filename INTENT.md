# INTENT.md: one-page product brief

**Product:** [Product name] · **Team:** [Names] · **Product Page:** [Link]

## 1. Who is it for?

- **The person:** Dance team leaders and choreographers who plan or edit formations for performances, including adapting formations when dancers are missing.
- **How you'll reach them to test:** Use NYU dance club captains as an initial recruiting channel; invite captains to recruit choreographers for early demos and testing.

## 2. Their workflow today, and with your product

- **Today (before):** Choreographers spend hours manually dragging 15–25 dancer dots in ArrangeUs when revising formations or adjusting for missing dancers.
- **With your product (after):** Choreographers use an AI-assisted stage-blocking web app to edit a formation, see suggested adjustments and visual geometry flags, then review and make each change on the stage canvas.

## 3. Your core claim

Choreographers can revise a formation or adapt it for missing dancers faster than manually repositioning 15–25 dots, while seeing geometry issues before approving edits.

## 4. Why not just use a plain AI chat?

The app represents dancers as positions on a stage and shows proposed changes directly on a canvas. Deterministic geometry checks—not the LLM—flag stage-boundary, minimum-spacing, and sprint-distance issues, making the result inspectable rather than relying on chat output alone.

## 5. Where a person checks the AI

The choreographer reviews every proposed change on the canvas and must personally drag or approve each edit; no edit is applied automatically.

## 6. What one run costs

- **Cost per run:** Approximately `$0.001` (estimate)
- **How you measured it:** Planning estimate; validate against actual provider usage and pricing.

## 7. Your first 50 users

Start with NYU dance club captains: invite captains to try the app, recruit choreographers from their teams for early tests, and use captain referrals to reach the first 50 users.

## 8. Not building (yet)

- Automatic approval or application of formation edits.
- Replacing the choreographer's judgment with AI.
- [Other out-of-scope work]

## 9. Riskiest assumption

Choreographers will trust and prefer canvas-based suggestions with visible geometry flags over manually adjusting formations in ArrangeUs. Test this with dance team leaders and choreographers recruited through NYU dance club captains.
