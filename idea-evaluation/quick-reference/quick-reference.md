# Idea Evaluation - Quick Reference

## When to Use

**Use this skill when:**
- ✅ Completed ideation-scamper (have 30-50+ ideas)
- ✅ Need to prioritize and select top ideas
- ✅ Want objective, multi-criteria scoring
- ✅ Need to defend idea selection to stakeholders

**Don't use when:**
- ❌ Only have 3-5 ideas (skip to critical-validation)
- ❌ Already know which idea to build (go validate it)
- ❌ Just brainstorming (do ideation first)

---

## Inputs Needed

**Required:**
- 20+ ideas from ideation-scamper
- PRFAQ and Closed World from solution-definition
- Customer-discovery outputs (JTBD, persona, evidence)

**Helpful to have:**
- Strategic priorities or constraints
- Resource availability (team size, timeline, budget)
- Competitive intelligence

---

## Outputs Produced

**1. Scored Ideas**
- Each idea rated 1-5 across 5 dimensions:
  - **Customer Value** (25%): Impact on JTBD
  - **Feasibility** (20%): Can we build it?
  - **Viability** (20%): Business sense?
  - **Desirability** (20%): Emotionally appealing?
  - **Strategic Fit** (15%): Advances vision?
- Weighted total score (1-5 scale)

**2. Ranked Ideas**
- Ideas sorted by score (highest to lowest)
- Top 10-15 ideas identified
- Clustering of related ideas

**3. Combined Concepts**
- Related ideas merged into stronger concepts
- Pattern recognition across SCAMPER techniques
- Top 3-5 ideas recommended for validation

---

## Time Estimate

**Standard Evaluation:** 1-2 hours
- Score 30-50 ideas across 5 dimensions
- Rank and cluster
- Identify top 3-5

**Quick Evaluation:** 30-45 minutes
- Score only most promising 15-20 ideas
- Focus on Customer Value + Feasibility only
- Quick ranking

**Deep Evaluation:** 2-4 hours
- Custom weighting strategy
- Sensitivity analysis
- Portfolio balancing (quick wins + moonshots)

---

## How to Use

### Weighting Strategy Selection

**Standard Balanced** (default):
```
Use idea-evaluation skill with standard balanced weighting.
```
- Customer Value: 25%, Feasibility: 20%, Viability: 20%, Desirability: 20%, Strategic Fit: 15%
- Best for: Mature companies with balanced priorities

**Other strategies available:**
- **Fast Follower:** Feasibility 30%, Viability 25%, Customer Value 25%
- **Disruptive Innovation:** Customer Value 30%, Strategic Fit 30%, Desirability 20%
- **Early Stage/PMF:** Customer Value 30%, Desirability 25%, Strategic Fit 25%
- **Resource-Constrained:** Feasibility 35%, Viability 30%, Customer Value 20%
- **B2B Enterprise:** Customer Value 30%, Feasibility 30%, Viability 20%
- **B2C Consumer:** Desirability 30%, Customer Value 25%, Strategic Fit 20%

### Scoring Approach

**All ideas at once:**
```
Evaluate all 47 ideas from my SCAMPER session using B2C Consumer weighting.
```

**One dimension at a time** (recommended for consistency):
```
Score all ideas on Customer Value first, then Feasibility, etc.
```

---

## Key Reminders

### Score Relatively, Not Absolutely
- Don't score ideas in isolation
- Compare: "Is Idea A better than Idea B on Customer Value?"
- This ensures differentiation

### Use Evidence, Not Gut
- Ground scores in Closed World (Feasibility)
- Reference PRFAQ (Customer Value, Strategic Fit)
- Use persona and evidence (Desirability)

### Document Extreme Scores
- If you score 1 or 5, note why
- These become assumptions to test in validation

### Embrace Uncertainty
- **3 = "decent but uncertain"** is valid
- Validation will resolve uncertainty

---

## The 5 Evaluation Dimensions

**Customer Value (Impact on JTBD)**
- How much does this solve customer pains?
- How many gains does it create?
- How much better/faster/cheaper?

**Feasibility (Can We Build It?)**
- Technical feasibility (tech exists? we have skills?)
- Operational feasibility (processes support it?)
- Resource availability (time, budget, people?)
- Dependencies (how many unknowns?)

**Viability (Business Sense?)**
- Revenue potential
- Cost structure and margins
- Pricing (will customers pay?)
- Unit economics at scale

**Desirability (Emotionally Appealing?)**
- Emotional resonance (will they love it?)
- Brand fit
- Differentiation from competitors
- Shareability (word-of-mouth potential)

**Strategic Fit (Advances Vision?)**
- Competitive advantage created
- Vision alignment
- Learning value
- Platform potential (unlocks future opportunities)

---

## Common Pitfalls

**1. Feasibility Bias**
- **Symptom:** All top ideas are "easy to build"
- **Fix:** Reduce Feasibility weight, increase Customer Value/Strategic Fit

**2. Founder's Favorite**
- **Symptom:** One idea scores 5s across board
- **Fix:** Score that idea last, compare to others objectively

**3. Analysis Paralysis**
- **Symptom:** Debating 3.2 vs 3.4
- **Fix:** Use integers (1-5), move quickly, trust the process

**4. Ignoring Must-Haves**
- **Symptom:** Top idea violates hard constraint
- **Fix:** Quick-filter for deal-breakers BEFORE scoring

**5. Scoring in Isolation**
- **Symptom:** Every idea gets 3s
- **Fix:** Force relative comparison - rank ideas against each other

---

## Next Steps After Evaluation

**Immediate next phase:**
```
Use critical-validation skill on top-ranked idea.
[Paste idea details, score, and concerns]
```

**What you'll do:**
- Six Thinking Hats validation (White → Red → Yellow → Black → Green → Blue)
- Test critical assumptions
- Make go/no-go/iterate decision
- Output: Validated idea ready for implementation OR modified concept for re-validation

---

## Integration with Other Skills

**Builds on:**
- ideation-scamper (Ideas to evaluate)
- solution-definition (Closed World for Feasibility, PRFAQ for Strategic Fit)
- customer-discovery (JTBD for Customer Value, evidence for competitive landscape)

**Feeds into:**
- critical-validation (Top 3-5 ideas get deep validation)

---

## Example Prompt

```
I've completed SCAMPER ideation for FairCredit (Nigeria mobile micro-lending) and
generated 63 ideas across all 7 techniques.

Use idea-evaluation skill with Early Stage/PMF weighting (Customer Value 30%,
Desirability 25%, Strategic Fit 25%, Feasibility 15%, Viability 5%).

Score all ideas, rank them, and identify top 5 for validation.

[Paste all 63 ideas]
[Include PRFAQ, Closed World, JTBD for reference]
```

---

## Files to Reference

**Detailed methodology:**
- `references/evaluation-framework.md` - Scoring criteria, weighting strategies, best practices

**Complete examples:**
- `references/example-outputs.md` - Evaluation results for 4 case studies showing:
  - How 50+ ideas were scored
  - Top 10 ranking
  - Idea clustering and combination
  - Top 3 selected for validation

---

## Success Criteria

**Good evaluation produces:**
- ✅ Clear score differentiation (not all 3s)
- ✅ Top 10 ideas span different SCAMPER techniques
- ✅ Mix of quick wins (high Feasibility) + moonshots (high Customer Value/Strategic Fit)
- ✅ Rationale for extreme scores documented
- ✅ Top 3-5 ideas clearly stand out

**Warning signs of weak evaluation:**
- ❌ All ideas cluster around 3.0-3.2 (no differentiation)
- ❌ Top 10 all from one SCAMPER technique (bias)
- ❌ Top idea violates known constraint
- ❌ Can't explain why top idea scored higher than #11

---

## Tips for Success

**Do:**
- Score one dimension at a time across all ideas
- Document why you gave 1s or 5s
- Look for patterns (certain SCAMPER types score higher?)
- Balance portfolio (quick wins + strategic bets)
- Use weights that match your strategic context

**Don't:**
- Spend >30 min debating decimal precision
- Let one person's favorite dominate (use independent scoring)
- Ignore correlation (breakthrough innovations trade feasibility for impact)
- Pick top 3 purely by score (consider portfolio balance)
- Skip this phase (gut feel alone is dangerous)

---

## Weighting Decision Guide

**Choose based on your context:**

**Balanced (default):** Mature company, balanced priorities
**Fast Follower:** Need revenue soon, proven models preferred
**Disruptive:** Well-funded, pursuing breakthrough innovation
**Early Stage:** Seeking product-market fit, can pivot
**Resource-Constrained:** Small team, limited budget, must ship
**B2B Enterprise:** Long sales cycles, large organizations
**B2C Consumer:** Mass market, viral growth potential

---

## Score Interpretation

**4.0 - 5.0:** Top tier - validate immediately
**3.5 - 3.9:** Strong - likely top 10, investigate why not higher
**3.0 - 3.4:** Moderate - decent but notable weaknesses
**2.5 - 2.9:** Weak - concerns outweigh strengths
**< 2.5:** Eliminate - critical flaws

---

## Portfolio Balancing

Don't just pick top 3 by score. Balance:
- **Horizons:** Core product improvements + new opportunities
- **Risk:** Safe bets + bold experiments
- **SCAMPER diversity:** Not all ELIMINATE or all COMBINE
- **Timeline:** Quick wins + long-term strategic moves

---

**Time investment:** 1-2 hours
**Next skill:** critical-validation (for top 3-5 ideas)
**Output format:** Scored and ranked idea list with top 3-5 highlighted
