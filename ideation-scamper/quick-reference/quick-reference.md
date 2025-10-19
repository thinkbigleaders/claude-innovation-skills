# Ideation SCAMPER - Quick Reference

## When to Use

**Use this skill when:**
- ✅ Completed solution-definition (have PRFAQ + Closed World)
- ✅ Need to generate many diverse innovative ideas
- ✅ Want systematic creative thinking across 7 techniques
- ✅ Ready to expand solution possibilities

**Don't use when:**
- ❌ Haven't defined solution vision yet (do solution-definition first)
- ❌ Just need one focused technique (use individual scamper-[technique] skills)
- ❌ Already have 20+ ideas to evaluate

---

## Inputs Needed

**Required:**
- PRFAQ (press release + FAQ) from solution-definition
- Closed World map (internal + external components)

**Helpful to have:**
- Constraints or focus areas
- Inspiration from evidence gathering
- Strategic priorities

---

## Outputs Produced

**30-50+ Ideas across 7 SCAMPER techniques:**

1. **SUBSTITUTE** (5-8 ideas) - Replace components
2. **COMBINE** (5-8 ideas) - Merge components
3. **ADAPT** (5-8 ideas) - Borrow from other contexts
4. **MODIFY** (5-8 ideas) - Change attributes/scale
5. **PUT TO OTHER USES** (4-6 ideas) - Repurpose components
6. **ELIMINATE** (5-8 ideas) - Remove to simplify
7. **REVERSE** (4-6 ideas) - Flip or reorder

Each idea includes:
- Brief description (1-2 sentences)
- Rationale (why this could work)
- Closed World component(s) involved

---

## Time Estimate

**Full SCAMPER Session:** 60-90 minutes
- 8-12 minutes per technique
- 7 techniques total

**Focused Session (3-4 techniques):** 30-45 minutes
- Choose techniques based on strategic goals
- Example: ELIMINATE + REVERSE for disruption

**Individual Technique:** 10-15 minutes
- Use standalone scamper-[technique] skills

---

## How to Use

### Mode Selection

**Interactive Mode** (recommended for first-timers):
```
Use ideation-scamper skill in interactive mode.
[Paste PRFAQ + Closed World]
```
- Claude generates ideas for one technique at a time
- You review after each technique before moving forward
- Can pivot focus based on what's working

**Autonomous Mode** (for experienced users):
```
Use ideation-scamper skill in autonomous mode.
[Paste PRFAQ + Closed World]
```
- Claude generates all 30-50+ ideas across all 7 techniques
- Faster, complete portfolio in one pass
- Review entire set afterward

### Technique Selection

**All 7 techniques** (recommended):
- Most diverse idea portfolio
- Uncovers non-obvious opportunities
- Balances incremental and disruptive

**Focused subset:**
- **For disruption:** ELIMINATE + REVERSE
- **For bundling:** COMBINE + ADAPT
- **For simplification:** ELIMINATE + MODIFY
- **For new markets:** PUT TO OTHER USES + ADAPT

---

## Key Reminders

### Quantity Over Quality
Generate many ideas quickly. Evaluation comes next - don't self-censor during ideation.

### Use Closed World Components
Each idea should reference specific components from your Closed World map. This grounds creativity in your actual resources.

### SCAMPER Technique Discipline
Stay within one technique at a time. Don't mix COMBINE with ELIMINATE thinking - they're different modes.

### Global Context
Reference persona and cultural context from customer-discovery when ideas involve local adaptation.

---

## SCAMPER Techniques Quick Guide

**SUBSTITUTE** - Replace X with Y
- Technology, materials, processes, channels, roles
- Example: Replace credit score with merchant trust score

**COMBINE** - Merge X and Y
- Features, services, data, roles, purposes
- Example: Combine loan with business training

**ADAPT** - Borrow from Z context
- Cross-industry, biomimicry, cross-cultural, historical
- Example: Adapt Uber surge pricing to lending rates

**MODIFY** - Change attribute of X
- Magnify, minify, speed up, slow down, change frequency
- Example: Magnify repayment from monthly to daily

**PUT TO OTHER USES** - Repurpose X for Y
- New users, new problems, new contexts, waste-to-value
- Example: Use transaction data for business insights, not just credit

**ELIMINATE** - Remove X entirely
- Features, steps, requirements, intermediaries, choices
- Example: Eliminate smartphone app, use SMS only

**REVERSE** - Flip X or reorder Y
- Process order, roles, direction, timing, ownership
- Example: Reverse pricing—borrowers set rate, lenders compete

---

## Common Pitfalls

**1. Self-Censoring Too Early**
- **Symptom:** "That won't work" during ideation
- **Fix:** Generate first, evaluate later. Bad ideas spark good ideas.

**2. Not Using Closed World**
- **Symptom:** Ideas unrelated to actual components
- **Fix:** Each idea must reference specific Closed World component(s)

**3. Mixing Techniques**
- **Symptom:** COMBINE idea that's actually ADAPT
- **Fix:** One technique at a time. If unsure, pick one and move on.

**4. Too Generic**
- **Symptom:** "Make it better/faster/cheaper"
- **Fix:** Be specific - WHAT to substitute/combine/eliminate and HOW

**5. Stopping at 3-5 Ideas Per Technique**
- **Symptom:** Running out of ideas quickly
- **Fix:** Push to 6-8 per technique. Best ideas come when you stretch.

---

## Next Steps After Ideation

**Immediate next phase:**
```
Use idea-evaluation skill
[Paste all SCAMPER ideas]
```

**What you'll do:**
- Rate ideas across 5 dimensions (Customer Value, Feasibility, Viability, Desirability, Strategic Fit)
- Rank and select top 10-15 ideas
- Combine/cluster related ideas
- Output: Top 3-5 ideas for critical validation

---

## Integration with Other Skills

**Builds on:**
- solution-definition (PRFAQ provides vision, Closed World provides components)
- customer-discovery (Persona and pains inspire ideas)

**Feeds into:**
- idea-evaluation (All ideas get scored and ranked)
- critical-validation (Top ideas validated with Six Thinking Hats)

---

## Example Prompt

```
I've completed solution-definition for mobile micro-lending in Lagos, Nigeria.

PRFAQ: FairCredit provides instant micro-loans via SMS to market traders without
smartphones or bank accounts, using merchant trust networks for credit assessment.

Closed World Internal: SMS interface, USSD menus, merchant network, trust algorithm,
loan database, repayment tracking, mobile money integration, transaction history

Closed World External: Feature phones, mobile networks, mobile money (M-Pesa),
market associations, existing merchants, competitors, regulations

Use ideation-scamper skill in interactive mode to generate ideas across all 7 techniques.
```

---

## Files to Reference

**Detailed methodology:**
- `references/scamper-framework.md` - Each technique explained with prompts

**Complete examples:**
- `references/example-outputs.md` - Full SCAMPER sessions for 4 case studies
  - 63 ideas for FairCredit (Nigeria)
  - 49 ideas for AsyncFlow (Singapore)
  - 54 ideas for SolarSeva (India)
  - 47 ideas for Unbroken (Sweden)

**Ready-to-use template:**
- `assets/scamper-template.md` - Structure for capturing ideas

---

## Success Criteria

**Good SCAMPER session produces:**
- ✅ 30-50+ total ideas across all techniques
- ✅ 5-8 ideas per major technique (SUBSTITUTE through ELIMINATE)
- ✅ Each idea references specific Closed World component(s)
- ✅ Mix of incremental and disruptive ideas
- ✅ Some ideas feel uncomfortable/challenging (pushing boundaries)
- ✅ Clear rationale for why each idea could work

**Warning signs of weak ideation:**
- ❌ Only 10-15 total ideas (not enough divergence)
- ❌ All ideas are incremental improvements (no bold moves)
- ❌ Ideas don't reference Closed World components
- ❌ Generic ideas that could apply to any product
- ❌ All ideas in one category (e.g., only COMBINE, no ELIMINATE)

---

## Tips for Success

**Do:**
- Push for 5-8 ideas per technique (quantity breeds quality)
- Reference Closed World components explicitly in each idea
- Mix incremental (safe) with disruptive (bold) ideas
- Use customer-discovery pains as inspiration
- Embrace weird/uncomfortable ideas (they teach something)

**Don't:**
- Self-censor during ideation (that's evaluation's job)
- Skip techniques because "they won't work for us"
- Write vague ideas ("make it faster" without specifics)
- Stop when you hit 3 ideas per technique (keep pushing)
- Forget global/cultural context from persona

---

## SCAMPER Strategic Focus

**For different goals:**

**Disruption:** Focus on ELIMINATE + REVERSE
**Bundling/Integration:** Focus on COMBINE + ADAPT
**Simplification:** Focus on ELIMINATE + MODIFY
**New Markets:** Focus on PUT TO OTHER USES + ADAPT
**Differentiation:** Focus on REVERSE + SUBSTITUTE
**Efficiency:** Focus on ELIMINATE + MODIFY

---

## Individual Technique Skills

If you want to go deep on one technique instead of all 7:

- `/scamper-substitute` - Replace components
- `/scamper-combine` - Merge components
- `/scamper-adapt` - Borrow from other contexts
- `/scamper-modify` - Change attributes/scale
- `/scamper-put-to-other-uses` - Repurpose components
- `/scamper-eliminate` - Remove to simplify
- `/scamper-reverse` - Flip or reorder

Each standalone skill goes deeper with more prompts and patterns.

---

**Time investment:** 60-90 minutes (full session) or 10-15 minutes (one technique)
**Next skill:** idea-evaluation
**Output format:** List of 30-50+ ideas with descriptions and rationale
