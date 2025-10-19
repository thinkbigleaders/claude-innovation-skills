---
name: idea-evaluation
description: Systematically evaluate and rank innovation ideas using multi-criteria scoring. Rate ideas on customer value, feasibility, viability, desirability, and strategic fit. Apply weighted scoring to identify top 3-5 ideas for deeper validation. Use after SCAMPER ideation generates 20-50+ ideas.
---

# Idea Evaluation - Multi-Criteria Scoring

## Purpose

After generating 20-50+ ideas through SCAMPER ideation, you need a systematic way to evaluate and prioritize them. This skill helps you:
- Rate ideas objectively across multiple dimensions
- Apply weighted scoring based on your strategic priorities
- Identify the most promising 3-5 ideas for deeper validation
- Make data-informed decisions about which ideas to pursue

## When to Use This Skill

Use this skill when:
- You've completed SCAMPER ideation and have 20+ ideas to evaluate
- You need to narrow down to top ideas before investing in validation
- You want structured, defensible criteria for idea selection
- Multiple stakeholders need to agree on which ideas to pursue
- You're balancing competing priorities (innovation vs. feasibility, quick wins vs. long-term bets)

## Input Required

Before starting evaluation, you need:
1. **List of ideas** from SCAMPER ideation (20-50+ ideas)
2. **Closed World map** from solution-definition phase
3. **PRFAQ** to understand customer needs and strategic goals
4. **Strategic priorities** - what matters most right now (speed? impact? learning? revenue?)

## Evaluation Framework

### Five Evaluation Dimensions

**1. Customer Value (Impact on JTBD)**
How much does this idea help customers get their job done?
- Pain relief: How much does it reduce customer frustrations?
- Gain creation: How much does it enable desired outcomes?
- Job performance: How much better/faster/cheaper does it make the core job?

**2. Feasibility (Can We Build It?)**
How realistic is it to implement this idea?
- Technical feasibility: Do we have the technology/skills?
- Operational feasibility: Can our processes support it?
- Resource availability: Do we have time/budget/people?
- Dependencies: How many unknowns or external dependencies?

**3. Viability (Does It Make Business Sense?)**
Will this idea work as a business?
- Revenue potential: Can we monetize it?
- Cost structure: Is it economically sustainable?
- Pricing: Will customers pay enough to make it viable?
- Unit economics: Does the math work at scale?

**4. Desirability (Do Customers Want It?)**
How emotionally appealing is this idea to customers?
- Emotional resonance: Does it spark delight/excitement?
- Brand fit: Does it align with how customers see us?
- Differentiation: Is it meaningfully different from alternatives?
- Shareability: Will customers tell others about it?

**5. Strategic Fit (Does It Advance Our Vision?)**
How well does this align with strategic goals?
- Competitive advantage: Does it create defensible differentiation?
- Vision alignment: Does it move us toward our long-term vision?
- Learning value: Does it teach us something important?
- Platform potential: Can it unlock future opportunities?

### Scoring Scale (1-5)

**5 - Exceptional:** Best-in-class, transformative impact, clear path forward
**4 - Strong:** Significant positive impact, manageable challenges
**3 - Moderate:** Decent impact, notable trade-offs or uncertainties
**2 - Weak:** Marginal impact, significant concerns or barriers
**1 - Poor:** Minimal impact, critical flaws or deal-breakers

## Workflow

### Step 1: Quick Filter (5-10 minutes)
Before detailed scoring, do a quick pass:
- Remove duplicates or near-duplicates
- Eliminate ideas that clearly violate constraints (regulatory, ethical, technical impossibilities)
- Group similar ideas as variations
- **Result:** Reduce from 40-50 to 20-30 distinct ideas worth evaluating

### Step 2: Define Evaluation Criteria & Weights (10-15 minutes)
Decide what matters most for your context:

**Standard weighting (balanced innovation):**
- Customer Value: 25%
- Feasibility: 20%
- Viability: 20%
- Desirability: 20%
- Strategic Fit: 15%

**Example alternative weightings:**

*Fast follower / quick wins:*
- Feasibility: 30%
- Viability: 25%
- Customer Value: 25%
- Strategic Fit: 15%
- Desirability: 5%

*Disruptive innovation / moonshot:*
- Customer Value: 30%
- Strategic Fit: 30%
- Desirability: 20%
- Feasibility: 10%
- Viability: 10%

*Early stage / learning mode:*
- Customer Value: 30%
- Desirability: 25%
- Strategic Fit: 25%
- Feasibility: 15%
- Viability: 5%

Choose weights that reflect your current priorities and constraints.

### Step 3: Score Each Idea (30-60 minutes)
For each idea, score 1-5 on each dimension:

**Scoring tips:**
- Be honest - don't inflate scores to favor pet ideas
- Use evidence from Closed World and PRFAQ to ground scores
- Note key assumptions or uncertainties for each score
- Compare ideas to each other (relative scoring)
- If uncertain, err toward middle scores (2-3) rather than extremes

**Recommended approach:**
1. Score all ideas on ONE dimension at a time (e.g., score all on Customer Value first)
2. This ensures consistency and allows relative comparison
3. Review and adjust outliers
4. Add brief reasoning notes for scores below 2 or above 4

### Step 4: Calculate Weighted Scores (5 minutes)
For each idea:
- Multiply each dimension score by its weight
- Sum to get total weighted score (max 5.0)
- Rank ideas from highest to lowest total score

**Example calculation:**
Idea: "Daily micro-payment repayments"
- Customer Value: 4 × 0.25 = 1.00
- Feasibility: 3 × 0.20 = 0.60
- Viability: 3 × 0.20 = 0.60
- Desirability: 4 × 0.20 = 0.80
- Strategic Fit: 5 × 0.15 = 0.75
- **Total: 3.75**

### Step 5: Analyze Results & Select Top Ideas (15-20 minutes)

**Review the ranking:**
- Identify top 10 ideas by weighted score
- Look for patterns (which dimensions drive high scores?)
- Check for surprises (ideas that scored higher/lower than expected)

**Apply filters and reality checks:**
- Minimum threshold: Consider only ideas scoring >3.0
- Must-haves: Filter for critical requirements
- Diversity: Ensure top ideas span different SCAMPER techniques
- Quick wins vs. long bets: Balance portfolio of ideas

**Select top 3-5 ideas for validation:**
- These will go to critical-validation phase (Six Thinking Hats)
- Aim for diversity: different types of innovations
- Include at least one "stretch" idea that challenges assumptions
- Document why these were selected

### Step 6: Create Evaluation Summary (10 minutes)
Document your evaluation:
- Criteria and weights used
- Full ranking of all ideas with scores
- Top 3-5 selected ideas with rationale
- Key insights from the evaluation process
- Next steps for validation

## Output Format

See `assets/evaluation-template.md` for ready-to-use template.

### Evaluation Summary Structure

```markdown
# Idea Evaluation Summary: [Product/Service Name]

## Evaluation Criteria & Weights

**Strategic Context:** [1-2 sentences: why these weights?]

- Customer Value: X%
- Feasibility: X%
- Viability: X%
- Desirability: X%
- Strategic Fit: X%

## Ideas Evaluated

**Total ideas generated:** X
**Ideas after quick filter:** X
**Ideas scored:** X

## Top 10 Ranked Ideas

| Rank | Idea | Customer Value | Feasibility | Viability | Desirability | Strategic Fit | **Total** |
|------|------|----------------|-------------|-----------|--------------|---------------|-----------|
| 1 | [Idea name] | 4.0 | 3.5 | 4.0 | 4.5 | 4.0 | **4.05** |
| 2 | [Idea name] | 3.5 | 4.0 | 3.5 | 3.5 | 4.5 | **3.75** |
| ... | ... | ... | ... | ... | ... | ... | ... |

## Selected Top 3-5 Ideas for Validation

### Idea 1: [Name]
**Weighted Score:** X.XX
**Why selected:** [1-2 sentences]
**Key strengths:** [bullets]
**Key concerns to validate:** [bullets]

### Idea 2: [Name]
[Same structure]

## Insights from Evaluation

**Patterns observed:**
- [What types of ideas scored highest?]
- [Which dimensions were hardest to score?]
- [Any surprises in the ranking?]

**Portfolio balance:**
- Quick wins: X ideas
- Strategic bets: X ideas
- Learning experiments: X ideas

## Next Steps

1. Deep validation of top 3-5 ideas using critical-validation skill (Six Thinking Hats)
2. [Other next steps specific to your context]
```

## Examples

See `references/example-outputs.md` for complete evaluation examples:
- FairCredit: Evaluating 20 micro-lending innovation ideas
- AsyncFlow: Evaluating 15 collaboration platform ideas
- SolarSeva: Evaluating 18 solar system innovations
- Unbroken: Evaluating 16 logistics resilience ideas

## Tips for Success

**Do:**
- **Be ruthless in quick filter** - eliminate weak ideas early to focus evaluation time
- **Score relative to each other** - "Is this idea better than that one on Customer Value?"
- **Use evidence** - refer to Closed World and PRFAQ when scoring Feasibility and Strategic Fit
- **Adjust weights** - if all ideas score similarly, reconsider your weights
- **Document reasoning** - especially for extreme scores (1-2 or 4-5)
- **Seek diversity** - top ideas should span different innovation types

**Don't:**
- **Over-analyze** - evaluation is not validation; save deep thinking for top 3-5
- **Fall in love with ideas** - score objectively even if you personally love an idea
- **Ignore gut feelings** - if scoring feels wrong, examine why (might reveal missing criteria)
- **Expect consensus** - different stakeholders may weight differently (that's okay!)
- **Treat scores as absolute truth** - they're decision aids, not guarantees

## Common Pitfalls

**1. Equal weighting trap**
Using 20% for all five dimensions means you haven't made strategic choices. Force yourself to prioritize.

**2. Feasibility bias**
Defaulting to "easy to build" ideas misses breakthrough innovations. Balance feasibility with customer value.

**3. Founder's favorite**
Don't inflate scores for your pet idea. Use evidence and compare objectively.

**4. Analysis paralysis**
Don't spend 2 hours debating whether an idea is a 3.2 or 3.4. Move quickly, trust the process.

**5. Missing must-haves**
Some ideas may score well but violate hard constraints (regulatory, ethical, brand). Filter these early.

## Integration Points

**Input from ideation-scamper:**
- List of 20-50+ SCAMPER-generated ideas
- Categorization by SCAMPER technique
- Quick filtering already reduced duplicates

**Input from solution-definition:**
- Closed World map informs Feasibility scores
- PRFAQ informs Customer Value and Strategic Fit
- Stakeholder FAQs reveal constraints affecting Viability

**Output to critical-validation:**
- Top 3-5 ideas with scores and rationale
- Key concerns to validate per idea
- Strategic context for validation priorities

## Customizing the Framework

**Add dimension for your context:**
- **Risk tolerance** - for conservative organizations
- **Speed to market** - when timing is critical
- **Regulatory compliance** - for heavily regulated industries
- **Team morale** - when engagement matters
- **Partner dependencies** - when ecosystem critical

**Adjust scoring scale:**
- Use 1-3 scale for faster evaluation (fewer nuances)
- Use 1-10 scale for fine-grained comparison (more time needed)
- Use Yes/No for must-have criteria before scoring

**Change workflow:**
- **Collaborative scoring:** Multiple people score independently, then discuss differences
- **Two-round scoring:** Quick scores first, then detailed review of top 15
- **Assumption-based scoring:** Mark which scores depend on unvalidated assumptions

## When to Re-Evaluate

Evaluation is a snapshot in time. Re-evaluate if:
- Major new information emerges (market shift, competitor launch, technology breakthrough)
- Strategic priorities change (new CEO, pivot, funding)
- Initial validation reveals assumptions were wrong
- 3-6 months pass (market and capabilities evolve)

## Next Steps

After completing idea evaluation:

1. **Document results:** Use template in `assets/evaluation-template.md`
2. **Communicate decisions:** Share rationale with stakeholders
3. **Validate top ideas:** Use `critical-validation` skill (Six Thinking Hats) on top 3-5
4. **Archive lower-ranked ideas:** Don't delete them; context may change
5. **Learn from process:** What surprised you? What would you weight differently next time?

Remember: Evaluation narrows options, validation tests assumptions. Don't confuse the two.
