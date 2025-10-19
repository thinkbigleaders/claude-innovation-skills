# Customer Discovery - Quick Reference

## When to Use

**Use this skill when:**
- ✅ Starting a new innovation project
- ✅ Validating an idea or opportunity
- ✅ Need to understand customer needs before building
- ✅ Have vague problem space, need structured understanding

**Don't use when:**
- ❌ Solution already defined and validated
- ❌ Just need to generate ideas (skip to ideation-scamper)
- ❌ Already have deep customer research

---

## Inputs Needed

**Minimum:**
- Problem space description (1-2 sentences)
- Target customer segment (general idea)

**Helpful to have:**
- Initial observations or pain points
- Market or industry context
- Geographic focus (if specific)

---

## Outputs Produced

**1. Jobs-to-be-Done Analysis**
- Functional, emotional, and social jobs
- Customer pains (obstacles, frustrations, risks)
- Customer gains (desired outcomes, benefits)

**2. Globally Diverse Persona**
- Name, age, location (with country and cultural context)
- Goals, challenges, behaviors
- Memorable quote in authentic voice

**3. Evidence Gathering**
- Findings from 2-4 sources (social media, competitors, research, customers)
- Validation or contradictions of assumptions
- Competitive landscape snapshot
- Customer quotes and pricing signals

---

## Time Estimate

**Quick Mode:** 1-2 hours
- Abbreviated JTBD
- Basic persona
- Limited evidence (1-2 sources)

**Standard Mode:** 4-8 hours (recommended)
- Full JTBD with depth
- Rich persona with cultural grounding
- Evidence from 3-4 sources

**Deep Mode:** 8-12 hours
- Extensive JTBD validation
- Multiple persona variants
- Comprehensive evidence across all 5 sources

---

## How to Use

### Mode Selection

**Interactive Mode** (recommended for first-timers):
```
Use customer-discovery skill in interactive mode for [problem space].
```
- Claude prompts you for input at each step
- You approve outputs before moving forward
- Checkpoints: After JTBD → After Persona → After Evidence

**Autonomous Mode** (for experienced users):
```
Use customer-discovery skill in autonomous mode for [problem space].
```
- Claude generates all three outputs based on initial prompt
- Faster but less customization
- Review and iterate afterward if needed

### Depth Selection

Specify evidence gathering depth:
```
Use customer-discovery with standard evidence gathering (3-5 hours).
```

Options:
- **Quick:** 1 hour, 1-2 sources, high-level findings
- **Standard:** 3-5 hours, 3-4 sources, pattern identification (recommended)
- **Deep:** 8+ hours, all 5 sources, comprehensive competitive analysis

---

## Key Reminders

### Global Diversity
**CRITICAL:** Personas should rotate through diverse geographies. Don't default to US/Western markets unless problem is region-specific.

Examples: Nigeria, Singapore, India, Kenya, Brazil, Indonesia, Mexico, Sweden

### Evidence Quality
- Focus on **patterns**, not exhaustive coverage
- Capture **direct quotes** in customer language
- Look for **contradictions** (they reveal complexity)
- **Recent evidence** matters (last 6-12 months)

### JTBD Depth
- Go beyond functional jobs to emotional and social
- Pains should be specific obstacles, not vague frustrations
- Gains should be concrete outcomes, not wishful thinking

---

## Common Pitfalls

**1. Western Bias**
- **Symptom:** Personas are always US/Europe-based
- **Fix:** Explicitly request "globally diverse persona from [Asia/Africa/Latin America/Middle East]"

**2. Surface-Level Evidence**
- **Symptom:** Just feature lists, no "why"
- **Fix:** Ask "Why do customers want this?" and "What job does this help them do?"

**3. Skipping Evidence Gathering**
- **Symptom:** Jumping straight to solution definition
- **Fix:** Even 1 hour of evidence beats pure assumptions

**4. Generic Personas**
- **Symptom:** "Small business owner, 35, likes efficiency"
- **Fix:** Add cultural context, specific behaviors, local payment methods, memorable details

**5. Analysis Paralysis**
- **Symptom:** Spending weeks researching
- **Fix:** Set time limit (3-5 hours evidence max), then synthesize and move forward

---

## Next Steps After Customer Discovery

**Immediate next phase:**
```
Use solution-definition skill
```

**What you'll do:**
- Write PRFAQ (press release + FAQ) using your JTBD and persona
- Map Closed World (internal and external components)
- Output: Solution vision ready for ideation

---

## Integration with Other Skills

**Feeds into:**
- solution-definition (JTBD informs PRFAQ, persona grounds customer testimonial)
- ideation-scamper (pain points inspire ELIMINATE ideas, gains inspire COMBINE)
- idea-evaluation (evidence provides competitive landscape context)

**References back:**
- critical-validation (White Hat checks assumptions from customer discovery)

---

## Example Prompt

```
I'm exploring financial services for small market traders in emerging markets
who struggle with access to affordable credit and managing cash flow unpredictably.

Use customer-discovery skill in interactive mode with standard evidence gathering.

Make sure the persona is globally diverse - choose a region in Africa or Asia.
```

---

## Files to Reference

**Detailed methodology:**
- `references/jtbd-framework.md` - JTBD question flows and templates
- `references/persona-template.md` - Global diversity guidelines and structure
- `references/evidence-gathering.md` - Source selection and synthesis

**Complete examples:**
- `references/example-outputs.md` - 3 worked examples (Nigeria, Singapore, India)

**Ready-to-use template:**
- `assets/customer-discovery-template.md` - Copy and fill in

---

## Success Criteria

**Good customer discovery produces:**
- ✅ Clear JTBD statement capturing functional + emotional + social dimensions
- ✅ Culturally-grounded persona team can empathize with
- ✅ 3-5 key evidence findings that validate or challenge assumptions
- ✅ Specific customer quotes in authentic language
- ✅ Understanding of "why now" (enabling factors)
- ✅ Gaps in current solutions identified

**Warning signs of shallow discovery:**
- ❌ JTBD is just "save time and money"
- ❌ Persona could be from anywhere (no cultural specificity)
- ❌ No contradictory evidence found
- ❌ No competitor landscape understanding
- ❌ Can't articulate why existing solutions fail

---

## Tips for Success

**Do:**
- Start with empathy, not solutions
- Embrace global diversity from the beginning
- Look for patterns across evidence sources
- Capture customer language verbatim
- Note what's NOT being said (silent needs)

**Don't:**
- Jump to solution ideas during discovery
- Default to Western contexts
- Rely on single evidence source
- Ignore contradictory findings
- Spend more than 8 hours on this phase

---

**Time investment:** 1-8 hours
**Next skill:** solution-definition
**Output format:** Markdown document with JTBD + Persona + Evidence
