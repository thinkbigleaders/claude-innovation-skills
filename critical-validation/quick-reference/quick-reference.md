# Critical Validation - Quick Reference

## When to Use

**Use this skill when:**
- ✅ Selected top 3-5 ideas from idea-evaluation
- ✅ Need deep validation before committing resources
- ✅ Want to test critical assumptions systematically
- ✅ Stakeholders need confidence for go/no-go decision
- ✅ Scores were close, need deeper analysis to decide

**Don't use when:**
- ❌ Haven't narrowed to top ideas yet (do idea-evaluation first)
- ❌ Idea is obviously flawed (just eliminate it)
- ❌ Already validated and ready to build

---

## Inputs Needed

**Required:**
- One idea to validate (don't try multiple in one session)
- Evaluation score and ranking
- Closed World map (for feasibility grounding)
- PRFAQ (for vision and benefits)

**Helpful to have:**
- 3-5 critical assumptions identified
- Evaluation concerns or questions
- Subject matter experts available

---

## Outputs Produced

**1. Comprehensive Six Hats Analysis**
- **White Hat:** Facts vs assumptions vs gaps
- **Red Hat:** Emotional reactions (initial and final)
- **Yellow Hat:** Benefits (customer, business, strategic)
- **Black Hat:** Risks (7 categories explored)
- **Green Hat:** Creative solutions to risks, idea modifications
- **Blue Hat:** Synthesis and decision

**2. Decision: GO / NO-GO / ITERATE**
- Clear rationale for decision
- Critical assumptions that must be true
- Risk mitigation strategies
- Next steps and action items

**3. Validation Summary**
- Key facts, benefits, risks, solutions
- Confidence level
- Review checkpoint planned

---

## Time Estimate

**Full Validation:** 90-120 minutes per idea
- Red (5 min) → White (15) → Yellow (20) → Black (20) → Green (20) → Blue (15) → Red (5)
- Recommended for major decisions

**Quick Validation:** 30-45 minutes per idea
- Red (3 min) → Yellow (10) → Black (15) → Blue (10)
- Use for straightforward ideas or preliminary validation

**Deep Dive:** 2-3 hours per idea
- Full validation + second round on MVP version
- Use for strategic bets or high uncertainty

---

## How to Use

### The Six Thinking Hats Sequence

**Full validation sequence** (recommended):
```
Use critical-validation skill on [Idea Name] with full validation sequence.

Idea: [Description]
Score: 3.85 (#2 of 63 ideas)
Key concerns: [From evaluation]

[Include Closed World and PRFAQ]
```

**Quick validation:**
```
Use critical-validation skill on [Idea Name] with quick validation (Red-Yellow-Black-Blue only).
```

### Hat Descriptions

**🤍 White Hat - Facts & Information**
- What we KNOW (facts, data, evidence)
- What we THINK we know (assumptions)
- What we DON'T know (gaps)
- What we NEED to learn (research required)

**❤️ Red Hat - Emotions & Intuition**
- Gut feelings, emotional reactions
- **NO JUSTIFICATION** - just express feelings
- Valid: "I'm excited" / "I feel nervous" / "Something feels off"
- **WRONG:** "I'm excited because..." (stop at the feeling!)

**💛 Yellow Hat - Benefits & Optimism**
- Customer benefits, business benefits, strategic benefits
- Best-case scenarios
- Why this could succeed

**🖤 Black Hat - Risks & Caution**
- Customer, technical, operational, business, competitive, execution risks
- Critical assumption risks
- Why this could fail

**💚 Green Hat - Creativity & Alternatives**
- Creative solutions to Black Hat risks
- Idea modifications and simplifications
- Alternative approaches

**🔵 Blue Hat - Process & Decisions**
- Synthesize learnings
- Identify critical assumptions
- Decide: GO / NO-GO / ITERATE
- Define next steps

---

## Key Reminders

### One Hat at a Time
**CRITICAL:** Don't mix perspectives. When wearing Yellow Hat, only explore benefits. Save risks for Black Hat.

### Red Hat Rules
**NO "BECAUSE"** - Just express feelings, no explanations.
- ✅ RIGHT: "I feel nervous."
- ❌ WRONG: "I feel nervous because we lack technical skills."

### Black Hat is Not Argument
Frame as "What risks exist?" not "Why is your idea bad?"
Black Hat identifies risks objectively, not attacks people.

### Green Hat Solves Black Hat
Each Green Hat solution should map to a specific Black Hat risk identified.

### Start and End with Red Hat
Initial Red Hat captures gut before logic. Final Red Hat checks if analysis changed intuition.

---

## Common Pitfalls

**1. Skipping to Decision**
- **Symptom:** Starting with Blue Hat
- **Fix:** Work through all hats first

**2. Red Hat Gets Justified**
- **Symptom:** "I feel nervous because..."
- **Fix:** No "because" allowed. Stop at feeling.

**3. Black Hat Becomes Argument**
- **Symptom:** Attacking each other's positions
- **Fix:** Frame as objective risk identification

**4. Yellow Hat Blindness**
- **Symptom:** Rushing Yellow because "we know the benefits"
- **Fix:** Force 20 minutes - stretch to find all benefits

**5. Green Hat Avoids Problems**
- **Symptom:** Generating new ideas instead of solving Black Hat risks
- **Fix:** Explicitly map each Green solution to a Black risk

**6. White Hat Becomes Debate**
- **Symptom:** Arguing if something is fact or assumption
- **Fix:** If debatable, it's an assumption. Move on.

---

## Next Steps After Validation

### If GO Decision:
- Begin implementation with risk mitigation built in
- Execute next steps from Blue Hat
- Schedule review checkpoint

### If ITERATE Decision:
- Build MVP or test assumptions first
- Use Green Hat modifications
- Re-validate after testing
- Decide again based on learnings

### If NO-GO Decision:
- Archive learnings
- Move to next idea from evaluation ranking
- Document what we learned

**Next skill (if Black Hat reveals hard technical problems):**
```
Use technical-breakthrough skill (TRIZ)
```

---

## Integration with Other Skills

**Builds on:**
- idea-evaluation (Top 3-5 ideas selected, scores and concerns identified)
- solution-definition (Closed World grounds White/Black Hats, PRFAQ grounds Yellow Hat)
- customer-discovery (JTBD validates customer benefits)

**Feeds into:**
- Implementation (GO decision)
- MVP testing (ITERATE decision)
- technical-breakthrough (if Black Hat reveals contradictions)

---

## Example Prompt

```
I've selected "USSD for Feature Phones" as my top idea from evaluation (score 4.2, #1 of 19 concepts).

Idea: Enable full FairCredit loan application and management via USSD menus on feature
phones, eliminating smartphone requirement entirely. Uses Closed World component: USSD
menus (new), feature phones (external), mobile networks (external).

Key concerns from evaluation:
- USSD UX is very limited (poor Desirability score: 2)
- Technical complexity unknown (Feasibility assumption)
- Will users actually adopt this? (Customer Value assumption)

Use critical-validation skill with full validation sequence (Red-White-Yellow-Black-Green-Blue-Red).

[Include Closed World, PRFAQ, and JTBD for reference]
```

---

## Files to Reference

**Detailed methodology:**
- Critical-validation SKILL.md has full workflow with prompts for each hat

**Complete examples:**
- `references/example-outputs.md` - 4 complete Six Hats validations:
  - FairCredit: "USSD for Feature Phones" (GO decision)
  - FairCredit: "Daily Micro-Payments" (ITERATE decision)
  - AsyncFlow: "Remove Real-Time Presence" (GO decision)
  - SolarSeva: "Grid-Tie Instead of Batteries" (GO decision)

**Ready-to-use template:**
- `assets/validation-template.md` - Structure for documenting session

---

## Success Criteria

**Good validation session produces:**
- ✅ Clear decision (go/no-go/iterate) with confidence
- ✅ 5-10 critical risks identified
- ✅ 3-5 risk mitigation strategies
- ✅ List of assumptions to test
- ✅ Team alignment on next steps
- ✅ Red Hat (final) shows gut aligns with Blue Hat decision

**Warning signs of poor validation:**
- ❌ No decision or "let's think about it more"
- ❌ Risks not identified (only optimism)
- ❌ No clear next steps
- ❌ Team still deeply divided
- ❌ Gut feeling and analysis completely contradict

---

## Tips for Success

**Do:**
- Enforce one hat at a time strictly
- Capture gut feeling in initial Red Hat before logic filters it
- Spend most time on Black and Green (risks and solutions matter most)
- Write everything down - don't trust memory
- Include skeptics - diverse perspectives surface blind spots
- Use timer to keep discussion focused

**Don't:**
- Skip hats - each perspective reveals something important
- Rush Black Hat - finding risks before building saves massive time/money
- Defend the idea - validation is about testing, not selling
- Mix optimism (Yellow) and pessimism (Black) - separate them
- Ignore Red Hat - if gut stays negative, that matters
- Allow "because" in Red Hat responses

---

## Decision Framework

**GO if:**
- Benefits clearly outweigh risks
- Risks have good mitigation strategies
- Critical assumptions testable before major investment
- Team confidence is high
- Gut feeling (final Red Hat) is positive

**NO-GO if:**
- Risks too high / benefits too uncertain
- Critical assumptions likely false
- Better alternatives exist
- Team gut feeling remains negative

**ITERATE if:**
- Good core idea but needs changes
- Test assumptions first, then decide
- Build MVP to learn, not full version
- Revisit after Green Hat modifications

---

## Red Hat Enforcement Rules

**These responses are WRONG (have justification):**
- ❌ "I'm excited because this solves a real pain"
- ❌ "I'm worried since we lack the technical skills"
- ❌ "I feel optimistic - customers will pay for this"

**These responses are RIGHT (pure emotion):**
- ✅ "I'm excited"
- ✅ "I'm worried"
- ✅ "I feel optimistic"
- ✅ "Something feels off"
- ✅ "I'm conflicted - excited and nervous at once"

**Facilitator script when someone justifies:**
> "Thank you for the feeling. Let's save the 'why' for White or Black Hat. Just the emotion for now."

---

## Adaptation Options

**Remote/Async validation:**
1. Send materials in advance
2. Each person completes each hat independently (written)
3. Facilitator synthesizes
4. Meeting to discuss and decide

**Short validation (30 min):**
- Red → Yellow → Black → Blue (skip White and Green)
- Good for time pressure or straightforward ideas

**Deep dive (3 hours):**
- Full sequence + second round on MVP version
- Good for major strategic bets

---

**Time investment:** 90-120 minutes per idea (full validation)
**Next skill:** Implementation (if GO) or technical-breakthrough (if hard problems)
**Output format:** Validation summary with decision, risks, solutions, next steps
