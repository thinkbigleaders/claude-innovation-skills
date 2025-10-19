# Solution Definition - Quick Reference

## When to Use

**Use this skill when:**
- ✅ Completed customer-discovery (have JTBD + persona + evidence)
- ✅ Ready to define what you'll build
- ✅ Need to align team on solution vision
- ✅ Want to work backwards from customer experience

**Don't use when:**
- ❌ Haven't done customer discovery yet (do customer-discovery first)
- ❌ Just exploring problem space (too early)
- ❌ Need ideas, not vision (skip to ideation-scamper)

---

## Inputs Needed

**Required:**
- Customer-discovery outputs (JTBD, persona, evidence)
- Problem space understanding
- Target customer segment

**Helpful to have:**
- Initial solution concept or hypothesis
- Constraints (technical, business, regulatory)
- Vision or strategic goals

---

## Outputs Produced

**1. PRFAQ (Press Release + FAQ)**
- 7-paragraph press release:
  - Headline, subheadline, location/date
  - Problem statement
  - Solution description
  - How it works
  - Customer testimonial quote (7-step anatomy)
  - How to get started
  - Call-to-action
- Customer FAQs (5-8 questions)
- Stakeholder FAQs (5-8 questions covering what we're NOT doing)

**2. Closed World Map**
- Internal components (8-15): what IS the product/service
- External components (5-10): what INTERACTS with the product
- Key relationships and constraints
- Innovation opportunities identified

---

## Time Estimate

**PRFAQ Only:** 2-4 hours
- Draft press release (1-2 hours)
- Iterate 3-5 times (30 min each)
- Customer + Stakeholder FAQs (1 hour)

**Full Solution Definition:** 3-6 hours (recommended)
- PRFAQ (2-4 hours)
- Closed World mapping (1-2 hours)

---

## How to Use

### Mode Selection

**Interactive Mode** (recommended):
```
Use solution-definition skill in interactive mode.
[Paste customer-discovery outputs]
```
- Claude drafts PRFAQ, you review and iterate
- Checkpoint after PRFAQ before Closed World
- You approve final vision before moving forward

**Autonomous Mode:**
```
Use solution-definition skill in autonomous mode.
[Paste customer-discovery outputs]
```
- Claude generates complete PRFAQ + Closed World
- Faster but less iteration
- Review and refine afterward if needed

---

## Key Reminders

### PRFAQ Iteration
**First draft is NEVER good enough.** Plan for 3-5 iterations:
1. First draft (structure and core ideas)
2. Customer testimonial depth (7-step anatomy)
3. Remove jargon and feature-speak
4. Strengthen emotional resonance
5. Polish and clarity

### Customer Testimonial Anatomy
Must include all 7 steps:
1. **Frustration:** What was broken before
2. **Discovery:** How they found your solution
3. **Benefits:** Tangible outcomes achieved
4. **Delightful moment:** Specific "wow" experience
5. **Transformation:** How life/work changed
6. **Advocacy:** Why they recommend it

### Closed World Scope
- **Internal components:** 8-15 (not 30, not 3)
- **External components:** 5-10
- If too many: group/cluster; if too few: decompose

---

## Common Pitfalls

**1. Feature List Instead of Press Release**
- **Symptom:** "It has X, Y, Z features"
- **Fix:** Focus on customer experience and outcomes, not technical capabilities

**2. Weak Customer Testimonial**
- **Symptom:** Generic quote like "This is great, I love it"
- **Fix:** Follow 7-step anatomy with specific details and emotional transformation

**3. Skipping Stakeholder FAQs**
- **Symptom:** Only customer FAQs
- **Fix:** Address "what we're NOT doing" to prevent scope creep

**4. Too Many Closed World Components**
- **Symptom:** 40+ components listed
- **Fix:** Stay at product/service level, not sub-components (e.g., "mobile app" not "login screen")

**5. No Iteration**
- **Symptom:** First draft accepted as final
- **Fix:** Iterate 3-5 times - PRFAQ quality directly impacts ideation quality

---

## Next Steps After Solution Definition

**Immediate next phase:**
```
Use ideation-scamper skill
[Paste PRFAQ + Closed World]
```

**What you'll do:**
- Generate 30-50+ innovative ideas across 7 SCAMPER techniques
- Use Closed World components as ideation substrate
- Output: Diverse idea portfolio ready for evaluation

---

## Integration with Other Skills

**Builds on:**
- customer-discovery (JTBD informs problem statement, persona grounds testimonial)

**Feeds into:**
- ideation-scamper (Closed World components are SCAMPER input, PRFAQ provides vision)
- idea-evaluation (PRFAQ vision helps score Strategic Fit)
- critical-validation (PRFAQ referenced in Yellow Hat benefits, Closed World grounds White Hat facts)

---

## Example Prompt

```
I've completed customer-discovery for mobile micro-lending for market traders in Lagos.

JTBD: Market traders need to access small loans quickly without smartphone
requirements or complex paperwork, because they have unpredictable cash flow
and traditional banks exclude them.

[Include full persona: Chidinma, etc.]

[Include evidence findings]

Use solution-definition skill in interactive mode to write PRFAQ and map Closed World.
```

---

## Files to Reference

**Detailed methodology:**
- `references/working-backwards.md` - Amazon PRFAQ framework and examples
- `references/closed-world-guide.md` - SIT Closed World principle explained

**Complete examples:**
- `references/example-outputs.md` - 4 complete PRFAQs + Closed Worlds
  - FairCredit (Nigeria fintech)
  - AsyncFlow (SE Asia B2B SaaS)
  - SolarSeva (India solar energy)
  - Unbroken (Sweden logistics)

**Ready-to-use template:**
- `assets/solution-definition-template.md` - PRFAQ + Closed World structure

---

## Success Criteria

**Good PRFAQ produces:**
- ✅ Headline captures essence in 5-10 words
- ✅ Problem statement directly maps to customer-discovery pains
- ✅ Customer testimonial follows 7-step anatomy with specific details
- ✅ Stakeholder FAQs address "what we're NOT doing"
- ✅ Reads like a real press release (not a spec doc)
- ✅ Emotionally resonant, not just functional

**Good Closed World map produces:**
- ✅ 8-15 internal components at right granularity
- ✅ 5-10 external components with clear interaction points
- ✅ Key relationships identified (dependencies, conflicts, synergies)
- ✅ Innovation opportunities surfaced (missing relationships, underutilized components)

**Warning signs of weak solution definition:**
- ❌ PRFAQ reads like feature list or spec
- ❌ Testimonial is generic or missing emotional transformation
- ❌ No stakeholder FAQs (scope creep risk)
- ❌ Closed World has 30+ components (too detailed)
- ❌ Only 1-2 iterations (not enough refinement)

---

## Tips for Success

**Do:**
- Iterate PRFAQ 3-5 times minimum
- Read testimonial out loud - does it sound authentic?
- Use persona voice and language from customer-discovery
- Keep Closed World at product level, not sub-components
- Address hard problems honestly in FAQs

**Don't:**
- Skip stakeholder FAQs (prevents "what about X?" later)
- Use jargon or technical language in press release
- Rush to Closed World before PRFAQ is solid
- Add components just because they might exist someday
- Assume first draft is good enough

---

## Working Backwards Principles

**From Amazon methodology:**
1. Start with customer experience, not technology
2. Work backwards from desired outcome
3. If hard to write press release, product is probably wrong
4. Testimonial authenticity signals product-market fit
5. FAQs force you to address hard questions upfront

---

**Time investment:** 3-6 hours
**Next skill:** ideation-scamper
**Output format:** Markdown document with PRFAQ + Closed World map
