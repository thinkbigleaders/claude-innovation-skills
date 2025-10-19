---
name: critical-validation
description: Deep-dive validation of top innovation ideas using Six Thinking Hats methodology. Systematically explore facts, emotions, benefits, risks, creative solutions, and decisions. Validates assumptions before committing resources. Use after idea-evaluation narrows to top 3-5 ideas.
---

# Critical Validation - Six Thinking Hats

## Purpose

After evaluation scores identify your top 3-5 ideas, you need deep validation before committing resources to implementation. This skill uses Edward de Bono's Six Thinking Hats methodology to:
- Systematically examine ideas from six complementary perspectives
- Surface hidden risks and opportunities evaluation missed
- Test critical assumptions before building
- Make go/no-go decisions with confidence
- Generate creative solutions to identified problems

## When to Use This Skill

Use this skill when:
- You've selected top 3-5 ideas from idea-evaluation
- Scores were close and you need deeper analysis to decide
- Stakeholders need confidence before greenlighting resources
- An idea seems promising but you sense hidden risks
- You want to stress-test assumptions before committing
- Team needs alignment on whether to proceed

## Input Required

Before starting validation, you need:
1. **Top 3-5 ideas** from idea-evaluation with scores and rationale
2. **Evaluation concerns** - what questions did scoring raise?
3. **Closed World map** to ground feasibility and risk discussion
4. **PRFAQ** to reference customer value and vision
5. **Critical assumptions** - what must be true for this to work?

## Execution Modes

Choose your preferred working mode:

### Interactive Mode (Recommended)

Claude will guide you through each hat sequentially, pausing for your review before moving to the next hat.

**Checkpoints:**
- After each hat → Review findings, add anything missed, approve before next hat
- Especially useful for Red Hat (capture gut feeling before logic)
- Final checkpoint before Blue Hat decision

**Use when:**
- First time using Six Thinking Hats
- Want to actively participate in each thinking mode
- Need team collaboration at each step
- Important decision requiring careful deliberation

### Autonomous Mode

Claude will complete all 6 hats in sequence and present comprehensive validation summary.

**Use when:**
- Familiar with Six Hats methodology
- Solo validation (not facilitating team session)
- Want complete analysis draft to review
- Time-constrained

**To activate:**
```
Use critical-validation skill in interactive mode on [Idea Name].
```

---

## The Six Thinking Hats

Each hat represents a distinct thinking mode. By wearing one hat at a time, teams think in parallel rather than arguing from fixed positions.

### 🤍 White Hat - Facts & Information
**Focus:** Objective data, what we know and don't know
- What facts do we have about this idea?
- What information is missing?
- What evidence supports or contradicts this?
- What do we need to research or validate?

**Output:** Clear picture of known facts vs. assumptions

---

### ❤️ Red Hat - Emotions & Intuition
**Focus:** Gut feelings, emotions, intuition (**NO JUSTIFICATION ALLOWED**)
- How do I feel about this idea?
- What's my gut reaction?
- Do I trust this will work?
- What emotions does this evoke?

**Output:** Honest emotional landscape, not filtered by logic

---

#### 🚨 Red Hat Enforcement Rules

**CRITICAL:** Red Hat responses must be PURE EMOTION with ZERO JUSTIFICATION.

**❌ WRONG Examples (include "because"/rationale):**
- "I'm excited because this solves a real customer pain"
- "I'm worried since we don't have the technical skills"
- "I feel optimistic - customers will definitely pay for this"
- "Something feels off about the pricing model"
- "I'm nervous about the timeline given our team size"

**✅ RIGHT Examples (pure feeling only):**
- "I'm excited"
- "I'm worried"
- "I feel optimistic"
- "Something feels off"
- "I'm nervous"
- "I'm conflicted - both excited and scared"
- "This feels right"
- "I don't trust this"

**Facilitator script when someone adds "because":**
> "Thank you for the feeling. Let's save the 'why' for White Hat or Black Hat. Just the emotion for now - how do you FEEL?"

**Why this matters:**
- Gut feelings often know things logic hasn't articulated yet
- Adding "because" turns Red Hat into White/Black Hat
- Pure emotions reveal team's intuitive assessment
- Final Red Hat shows if analysis changed gut feeling

**Enforcement checklist:**
- [ ] No "because" statements
- [ ] No explanations or reasons
- [ ] No data or facts
- [ ] Just emotions: excited, worried, nervous, optimistic, skeptical, confident, uncertain, etc.

---

### 💛 Yellow Hat - Benefits & Optimism
**Focus:** Positive outcomes, best-case scenarios, value
- What's great about this idea?
- What value does it create?
- What's the best-case outcome?
- Why will this succeed?

**Output:** Comprehensive map of potential benefits

---

### 🖤 Black Hat - Risks & Caution
**Focus:** Problems, risks, reasons it might fail
- What could go wrong?
- What are the risks?
- Why might this fail?
- What are we overlooking?

**Output:** Thorough risk inventory, Devil's advocate perspective

---

### 💚 Green Hat - Creativity & Alternatives
**Focus:** New ideas, creative solutions, alternatives
- How can we overcome Black Hat risks?
- What are alternative approaches?
- What if we modified this idea?
- How can we make this even better?

**Output:** Creative solutions to problems, idea improvements

---

### 🔵 Blue Hat - Process & Decisions
**Focus:** Meta-thinking, process control, synthesis
- What have we learned?
- What's the conclusion?
- What are next steps?
- Do we go, no-go, or iterate?

**Output:** Decision and action plan

---

## Recommended Validation Sequence

### Full Validation (90-120 minutes per idea)

**Sequence:** Red → White → Yellow → Black → Green → Blue → Red

1. **Red Hat (5 min):** Initial gut check - how do we feel?
2. **White Hat (15 min):** What facts do we know? What's missing?
3. **Yellow Hat (20 min):** Map all benefits and best-case scenarios
4. **Black Hat (20 min):** Identify all risks and failure modes
5. **Green Hat (20 min):** Creative solutions to Black Hat problems
6. **Blue Hat (15 min):** Synthesize and decide (go/no-go/iterate)
7. **Red Hat (5 min):** Final emotional check after analysis

**Why this sequence:**
- Start with Red to capture unfiltered intuition
- White grounds discussion in facts vs. assumptions
- Yellow before Black prevents premature negativity
- Green solves problems Black identified
- Blue synthesizes everything
- End with Red to check if analysis changed gut feeling

### Quick Validation (30-45 minutes per idea)

**Sequence:** Red → Yellow → Black → Blue

1. **Red Hat (3 min):** Initial gut check
2. **Yellow Hat (10 min):** Key benefits
3. **Black Hat (15 min):** Critical risks
4. **Blue Hat (10 min):** Decision

**When to use:** Time-constrained, straightforward ideas, preliminary validation

---

## Workflow

### Step 1: Prepare (10 minutes)

**Set up the session:**
- Select ONE idea to validate (don't try multiple ideas in one session)
- Review evaluation scores and concerns
- Identify 3-5 critical assumptions to test
- Gather materials: PRFAQ, Closed World, evaluation summary

**Assemble participants:**
- Idea owner/champion
- Subject matter experts (tech, operations, business)
- Skeptic/Devil's advocate
- Facilitator (keeps group on hat, watches time)

**Set ground rules:**
- One hat at a time (no mixing perspectives)
- All voices heard (especially quiet members)
- No defending or attacking (just thinking)
- Write ideas down (don't trust memory)

### Step 2: Red Hat - Initial Gut Check (5 minutes)

**Prompt:** "How do you feel about this idea right now? What's your gut reaction?"

**Guidelines:**
- **NO JUSTIFICATION ALLOWED** - just express pure feelings
- **STOP at the emotion** - no "because", no explanations
- Valid responses: "I'm excited" / "I'm nervous" / "Something feels off" / "I'm conflicted"
- **INVALID:** Any response with "because", "since", or explanations
- Capture all reactions without judgment
- If majority is negative, consider stopping here

**Output:** Honest emotional baseline before analysis

**✅ CORRECT Example:**
- Person A: "I'm excited"
- Person B: "I'm worried"
- Person C: "I feel optimistic"

**❌ INCORRECT Example (includes justification):**
- Person A: "I'm excited but worried about technical complexity"
- Person B: "Gut says this is too risky right now"
- Person C: "I feel optimistic - customers will love this"

**If someone adds "because" or rationale:**
Facilitator says: "Thank you for sharing. Let's capture just the feeling for now - excited? worried? Save the 'why' for White Hat or Black Hat."

---

### Step 3: White Hat - Facts & Information (15 minutes)

**Prompt:** "What do we know for certain? What information is missing?"

**Four categories:**

**1. What we KNOW (facts, data, evidence):**
- Confirmed customer needs from research
- Technical capabilities from Closed World
- Market data from evidence gathering
- Competitor actions

**2. What we THINK we know (assumptions):**
- "Customers will pay for this" (assumed, not proven)
- "We can build this in 3 months" (estimate, not certain)
- "This will differentiate us" (hypothesis, not fact)

**3. What we DON'T know (gaps):**
- Will customers actually use this feature?
- What's the true technical complexity?
- How will competitors respond?

**4. What we NEED to learn (research needed):**
- User testing to validate X
- Technical spike to prove Y
- Competitive analysis of Z

**Output:** Clear map of knowledge vs. assumptions vs. gaps

**Example:**
```
KNOW:
- 45% of users requested similar feature in surveys
- We have 3 engineers with required skills

THINK WE KNOW:
- Users will pay 20% premium for this
- Implementation will take 4 months

DON'T KNOW:
- How often would users actually use this?
- What edge cases will we encounter?

NEED TO LEARN:
- Prototype + user test (2 weeks)
- Technical spike on integration (1 week)
```

---

### Step 4: Yellow Hat - Benefits & Optimism (20 minutes)

**Prompt:** "What's great about this idea? What value does it create? What's the best-case outcome?"

**Explore four benefit dimensions:**

**1. Customer benefits:**
- Jobs made easier/faster/cheaper
- Pains eliminated
- Gains created
- Delightful moments

**2. Business benefits:**
- Revenue opportunities
- Cost reductions
- Strategic advantages
- Competitive moats

**3. Strategic benefits:**
- Platform potential (unlocks future opportunities)
- Learning value (teaches us something critical)
- Market positioning
- Partnership opportunities

**4. Best-case scenarios:**
- If everything goes right, what happens?
- Network effects, viral growth
- Industry recognition

**Output:** Comprehensive value map (helps prioritize what to preserve)

**Example:**
```
CUSTOMER BENEFITS:
- Saves traders 2 hours/day (massive JTBD impact)
- Reduces stress of tracking manually

BUSINESS BENEFITS:
- Could increase retention by 30%
- Differentiates us from all competitors

STRATEGIC BENEFITS:
- Platform play - can build other features on this data
- Could license technology to partners

BEST CASE:
- Becomes the killer feature customers choose us for
- Industry standard, others copy us (validates leadership)
```

---

### Step 5: Black Hat - Risks & Caution (20 minutes)

**Prompt:** "What could go wrong? Why might this fail? What are we overlooking?"

**Explore seven risk categories:**

**1. Customer risks:**
- Won't pay for it
- Won't use it (low adoption)
- Doesn't actually solve pain
- Complexity overwhelms them

**2. Technical risks:**
- Harder to build than estimated
- Performance/scalability issues
- Integration nightmares
- Technical debt created

**3. Operational risks:**
- Support burden too high
- Can't maintain/update easily
- Training required for team
- Process changes needed

**4. Business risks:**
- Unit economics don't work
- Cannibalizes existing revenue
- Damages brand/reputation
- Legal/regulatory issues

**5. Competitive risks:**
- Competitors copy quickly
- Not differentiated enough
- Market moves away from this

**6. Execution risks:**
- Takes longer than planned
- Costs more than budgeted
- Team lacks skills
- Opportunity cost (should build X instead)

**7. Assumption risks:**
- Which White Hat assumptions are most dangerous if wrong?

**Output:** Comprehensive risk inventory (most important hat for avoiding failure)

**Example:**
```
CUSTOMER RISKS:
- Adoption might be slow (behavioral change required)
- Power users may find it limiting vs. manual control

TECHNICAL RISKS:
- Real-time sync could fail at scale (100k+ users)
- Edge cases we haven't thought of

OPERATIONAL RISKS:
- Customer support needs training on new feature
- Maintenance burden on small team

BUSINESS RISKS:
- Might cannibalize revenue from premium tier
- Legal risk if data handling isn't perfect

COMPETITIVE RISKS:
- Competitors can copy in 6 months
- Market trend toward different solution

EXECUTION RISKS:
- Estimated 3 months, could be 6+
- Requires hiring specialist we don't have
```

---

### Step 6: Green Hat - Creativity & Alternatives (20 minutes)

**Prompt:** "How can we overcome the risks identified? What creative solutions exist? How can we modify this idea?"

**Three approaches:**

**1. Risk mitigation (for each Black Hat risk):**
- How can we reduce likelihood?
- How can we reduce impact?
- What's the contingency plan?

**Example:**
```
BLACK HAT RISK: "Real-time sync might fail at scale"
GREEN HAT SOLUTIONS:
- Phase 1: Launch without real-time (async only)
- Technical spike to prove scalability before full build
- Partner with infrastructure expert
- Limit concurrent users initially
```

**2. Idea modifications:**
- Can we make this simpler (ELIMINATE something)?
- Can we make this modular (MVP first, expand later)?
- Can we test before building (prototype, wizard-of-oz)?

**Example:**
```
ORIGINAL IDEA: "AI-powered business insights dashboard"
GREEN HAT MODIFICATIONS:
- MVP: One insight, delivered weekly via SMS (not real-time dashboard)
- Test: Manually create insights for 20 users, see if valuable
- Modular: Start with spending analysis, add revenue insights later
```

**3. Alternative approaches:**
- What if we solved same problem differently?
- What can we borrow from other industries?
- What would [competitor/hero company] do?

**Output:** Creative solutions to risks, idea improvements, alternatives

---

### Step 7: Blue Hat - Process & Decisions (15 minutes)

**Prompt:** "What have we learned? What's the conclusion? Do we go, no-go, or iterate?"

**Synthesize the session:**

**1. Summary:**
- Key facts (White Hat)
- Biggest benefits (Yellow Hat)
- Critical risks (Black Hat)
- Best solutions (Green Hat)

**2. Critical assumptions identified:**
- What must be true for this to work?
- Which assumptions are testable?
- Which are make-or-break?

**3. Decision framework:**

**GO:** Build this idea as planned
- Benefits clearly outweigh risks
- Risks have good mitigation strategies
- Critical assumptions testable before major investment
- Team confidence is high

**NO-GO:** Don't pursue this idea
- Risks too high / benefits too uncertain
- Critical assumptions likely false
- Better alternatives exist
- Team gut feeling remains negative

**ITERATE:** Modify and re-validate
- Good core idea but needs changes
- Test assumptions first, then decide
- Build MVP to learn, not full version
- Revisit after Green Hat modifications

**4. Next steps (if GO or ITERATE):**
- What do we build/test first?
- What assumptions must we validate?
- Who owns this?
- What's the timeline?
- What's the budget?
- When do we review progress?

**Output:** Clear go/no-go/iterate decision with rationale and next steps

---

### Step 8: Red Hat - Final Gut Check (5 minutes)

**Prompt:** "After all this analysis, how do you feel now? Has your gut reaction changed?"

**Guidelines (SAME AS INITIAL RED HAT):**
- **NO JUSTIFICATION** - pure emotions only
- Just state feelings: "I feel confident" / "Still nervous" / "More excited now" / "Less certain"
- **NO "because"** statements

**Compare to initial Red Hat:**
- Are you more or less confident?
- Did analysis confirm or contradict intuition?
- Any lingering concerns?

**If gut feeling contradicts Blue Hat decision:**
- Why the disconnect?
- Is there a risk we haven't articulated?
- Trust the analysis or trust the gut?

**Output:** Emotional validation of decision, surface any unease

**✅ CORRECT Final Red Hat:**
- Person A: "I feel much more confident now"
- Person B: "Still nervous but less worried"
- Person C: "I'm excited"

**❌ INCORRECT Final Red Hat (includes justification):**
- Person A: "I feel more confident because we have mitigation strategies"
- Person B: "Still nervous about the technical risks"
- Person C: "I'm excited - this is going to work"

---

## Output Format

See `assets/validation-template.md` for ready-to-use template.

### Validation Summary Structure

```markdown
# Six Thinking Hats Validation: [Idea Name]

**Date:** [Date]
**Participants:** [Names and roles]
**Idea score:** X.XX (from evaluation)
**Session duration:** XX minutes

---

## Initial Red Hat - Gut Feelings

[Capture each person's initial reaction]

**Overall sentiment:** Positive / Mixed / Negative

---

## White Hat - Facts & Information

### What We KNOW:
- [Fact 1]
- [Fact 2]

### What We THINK We Know (Assumptions):
- [Assumption 1]
- [Assumption 2]

### What We DON'T Know:
- [Gap 1]
- [Gap 2]

### What We NEED to Learn:
- [Research need 1]
- [Research need 2]

---

## Yellow Hat - Benefits & Optimism

### Customer Benefits:
- [Benefit 1]
- [Benefit 2]

### Business Benefits:
- [Benefit 1]
- [Benefit 2]

### Strategic Benefits:
- [Benefit 1]
- [Benefit 2]

### Best-Case Scenario:
[Describe best possible outcome]

---

## Black Hat - Risks & Caution

### Customer Risks:
- [Risk 1]
- [Risk 2]

### Technical Risks:
- [Risk 1]
- [Risk 2]

### Operational Risks:
- [Risk 1]
- [Risk 2]

### Business Risks:
- [Risk 1]
- [Risk 2]

### Competitive Risks:
- [Risk 1]

### Execution Risks:
- [Risk 1]

### Critical Risk Assumptions:
- [Most dangerous assumption if wrong]

---

## Green Hat - Creative Solutions

### Risk Mitigation:
[For each critical Black Hat risk, propose solution]

### Idea Modifications:
[How could we improve/simplify this idea?]

### Alternative Approaches:
[Different ways to achieve same goal]

---

## Blue Hat - Decision & Next Steps

### Summary:
- **Key facts:** [from White Hat]
- **Biggest benefits:** [from Yellow Hat]
- **Critical risks:** [from Black Hat]
- **Best solutions:** [from Green Hat]

### Critical Assumptions:
1. [Assumption that must be true]
2. [Assumption that must be true]

### DECISION: [ GO / NO-GO / ITERATE ]

**Rationale:** [Why this decision?]

### Next Steps (if GO or ITERATE):
1. [Action 1] - Owner: [Name] - Due: [Date]
2. [Action 2] - Owner: [Name] - Due: [Date]

### Success Criteria:
[How will we know this is working?]

### Review Checkpoint:
[When will we review progress?]

---

## Final Red Hat - Gut Check

[How do people feel after analysis?]

**Confidence level:** High / Medium / Low
**Any lingering concerns:** [Yes/No and what]

---

## Sign-off

**Facilitator:** [Name]
**Decision owners:** [Names]
**Date:** [Date]
```

---

## Examples

See `references/example-outputs.md` for complete Six Thinking Hats validations:
- FairCredit: Validating "USSD for Feature Phones" (GO decision)
- FairCredit: Validating "Daily Micro-Payments" (ITERATE decision)
- AsyncFlow: Validating "Remove Real-Time Presence" (GO decision)
- SolarSeva: Validating "Grid-Tie Instead of Batteries" (GO decision)

---

## Tips for Success

**Do:**
- **Enforce one hat at a time** - mixing perspectives defeats the purpose
- **Start with Red Hat** - capture gut before logic filters it
- **Spend most time on Black and Green** - risks and solutions matter most
- **Write everything down** - don't trust memory, capture all ideas
- **Include skeptics** - diverse perspectives surface blind spots
- **Use timer** - keeps discussion focused and moving

**Don't:**
- **Skip hats** - each perspective reveals something important
- **Rush Black Hat** - finding risks before building saves massive time/money
- **Defend the idea** - validation is about testing, not selling
- **Mix optimism and pessimism** - separate Yellow and Black thinking
- **Ignore Red Hat** - if gut feeling stays negative, that matters

---

## Common Pitfalls

**1. Skipping to decision**
Starting with Blue Hat (decision) without working through other hats. Leads to poor decisions based on incomplete thinking.

**2. Black Hat becomes argument**
Black Hat degenerates into people attacking each other's positions rather than identifying risks objectively.
**Solution:** Frame as "What risks exist?" not "Why is your idea bad?"

**3. Yellow Hat blindness**
Skipping or rushing Yellow Hat because "we already know the benefits." Yellow reveals non-obvious value.
**Solution:** Force 20 minutes on Yellow - stretch to find all benefits.

**4. Green Hat avoids problems**
Green Hat generates new ideas instead of solving Black Hat risks.
**Solution:** Explicitly map Green solutions to Black risks.

**5. White Hat becomes debate**
Arguing about whether something is a fact or assumption.
**Solution:** If debatable, it's an assumption. Move on.

**6. Red Hat gets justified**
"I feel nervous because..." - stop at "I feel nervous."
**Solution:** No "because" allowed in Red Hat.

---

## Adapting the Method

### Short Validation (30 minutes)
Use only: Red → Yellow → Black → Blue

Good for: Straightforward ideas, time pressure, preliminary validation

### Deep Dive (3 hours)
Add second round: After Blue Hat decision, do another Yellow/Black/Green cycle on the MVP version.

Good for: Major strategic bets, high-uncertainty ideas

### Remote/Async Validation
1. Send materials in advance
2. Each person completes each hat independently (written)
3. Facilitator synthesizes
4. Meeting to discuss and decide

Good for: Distributed teams, busy stakeholders

### Collaborative Scoring
Use Six Hats to revisit evaluation scores:
- Did Black Hat reveal risks that lower Feasibility score?
- Did Yellow Hat reveal benefits that increase Customer Value?

Good for: When evaluation scores feel uncertain

---

## Integration Points

**Input from idea-evaluation:**
- Top 3-5 ideas with scores
- Key concerns noted during evaluation
- Critical assumptions flagged

**Input from solution-definition:**
- Closed World map (grounds White and Black Hats)
- PRFAQ (provides Yellow Hat benefits and vision)

**Output to implementation:**
- Clear go/no-go decision with rationale
- Risk mitigation strategies
- Assumptions to test first
- MVP definition (if ITERATE)

---

## When to Re-Validate

**Trigger re-validation if:**
- Initial implementation reveals new information
- Market conditions change significantly
- Critical assumption proves false
- 3-6 months pass without progress

**Re-validation process:**
- Review original validation notes
- Focus on what changed (White Hat - new facts)
- Update Black Hat with new risks
- Re-decide: continue, pivot, or stop

---

## Success Metrics

**Good validation session produces:**
- Clear decision (go/no-go/iterate) with confidence
- 5-10 critical risks identified
- 3-5 risk mitigation strategies
- List of assumptions to test
- Team alignment on next steps

**Warning signs of poor validation:**
- No decision or "let's think about it more"
- Risks not identified (only optimism)
- No clear next steps
- Team still deeply divided
- Gut feeling and analysis completely contradict

---

## Next Steps

After completing critical validation:

1. **If GO:** Begin implementation with risk mitigation built in
2. **If ITERATE:** Build MVP, test assumptions, re-validate
3. **If NO-GO:** Archive learnings, consider next idea from evaluation ranking
4. **Document:** Use template in `assets/validation-template.md`
5. **Review:** Schedule checkpoint to review progress and assumptions

If Black Hat reveals hard technical challenges, consider using the **technical-breakthrough** skill (TRIZ) to solve contradictions creatively.

---

## Remember

**Six Thinking Hats is not about consensus** - it's about exploring an idea thoroughly from all angles before deciding. Good validation might reveal an idea isn't worth pursuing - that's success, not failure. Better to learn in 90 minutes than after 6 months of building.

**Evaluation narrowed options. Validation tests assumptions. Don't confuse the two.**
