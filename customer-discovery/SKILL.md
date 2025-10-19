---
name: customer-discovery
description: Deep customer understanding through Jobs-to-be-Done analysis, globally diverse persona creation, and evidence gathering from real-world sources. Use when starting innovation projects to understand customer needs, validate assumptions, and gather market intelligence before defining solutions. First phase of systematic innovation.
---

# Customer Discovery: Understanding the Problem Space

## Purpose

Build deep, validated understanding of customer needs before jumping to solutions. Combines Jobs-to-be-Done analysis, persona creation with global diversity, and evidence gathering to create a solid foundation for innovation.

## When to Use This Skill

Use this skill when:
- Starting a new product or service innovation project
- Validating an idea or opportunity
- Need to understand customer needs deeply
- Want to avoid building solutions based on assumptions
- Preparing for solution definition and ideation

## Execution Modes

Before starting customer discovery, choose your preferred working mode:

### Interactive Mode (Recommended for First-Timers)

Claude will guide you step-by-step through each phase, asking for your input and approval before proceeding.

**Checkpoints:**
1. After JTBD analysis → Review and approve before creating persona
2. After persona creation → Review and approve before evidence gathering
3. After evidence gathering → Review final synthesis

**Use when:**
- First time using this skill
- Want hands-on involvement in each step
- Need to customize outputs based on emerging insights
- Prefer iterative refinement

### Autonomous Mode (For Experienced Users)

Claude will generate all three outputs (JTBD, persona, evidence) based on your initial prompt, then present complete customer discovery for your review.

**Use when:**
- Familiar with JTBD, personas, and evidence gathering
- Want fast first draft to iterate on
- Trust the framework to guide outputs
- Prefer batch review over step-by-step

**To activate a mode, simply state it in your prompt:**
```
Use customer-discovery skill in interactive mode for [problem space].
```
or
```
Use customer-discovery skill in autonomous mode for [problem space].
```

---

## Three-Step Process

### Step 1: Jobs-to-be-Done Analysis

Define what customers are truly hiring a product/service to accomplish in their lives.

**Explore three types of jobs:**
1. **Functional jobs:** Practical tasks and outcomes they need to accomplish
2. **Emotional jobs:** Feelings they want to experience or avoid
3. **Social jobs:** How they want to be perceived by others

**Identify pains and gains:**
- **Pains:** Current obstacles, frustrations, risks, undesired outcomes
- **Gains:** Desired benefits, required outcomes, unexpected delighters

**Output:** Job statement capturing functional, emotional, and social dimensions, plus comprehensive list of pains and gains.

**For detailed methodology:** Read `references/jtbd-framework.md` for question flows, templates, and examples.

### Step 2: Persona Creation (Globally Diverse)

Bring the JTBD to life with a specific, realistic persona that represents the target customer.

**CRITICAL: Create globally diverse personas** - Rotate through different regions and cultural contexts. Do NOT default to US/Western markets unless product is explicitly region-specific.

**Essential elements:**
- Basic profile (age, occupation, location with country, life stage)
- Context including cultural factors
- Goals and motivations (linked to JTBD)
- Challenges and frustrations (from JTBD pains)
- Behaviors including local payment methods and communication preferences
- Memorable quote in authentic voice

**Output:** Vivid, culturally-grounded persona that team can empathize with and design for.

**For detailed methodology:** Read `references/persona-template.md` for global diversity guidelines, structure, and examples from Nigeria, Singapore, India, and more.

### Step 3: Evidence Gathering

Validate assumptions and gather real-world intelligence before defining solutions.

**Choose depth level:**
- **Quick (1 hour):** 1-2 sources, high-level patterns, 3-5 findings
- **Standard (3-5 hours):** 3-4 sources, pattern identification, 8-12 findings **[Recommended]**
- **Deep (8+ hours):** All 5 sources, comprehensive analysis, 15-20+ findings

**Five evidence sources:**
1. **Social media listening:** Customer complaints, workarounds, discussions (enhanced with search templates)
2. **Market & competitor analysis:** What exists, gaps, pricing signals
3. **Customer feedback & support data:** Patterns in problems and requests
4. **Technology & trend scanning:** What's newly possible, "why now"
5. **Direct customer research:** Interviews, surveys, observation

**Output:** Synthesized findings that validate or challenge your JTBD/persona, reveal landscape, capture customer voice, and identify opportunities.

**For detailed methodology:** Read `references/evidence-gathering.md` for source selection, research questions, depth levels, social media search templates, and synthesis guides.

## Workflow

Follow these steps in sequence:

1. **Start with JTBD:** Understand the customer's job before anything else. This is your "why."

2. **Build persona:** Create specific person experiencing these jobs. **Ensure global diversity** - don't default to Western contexts.

3. **Gather evidence:** Validate your understanding with real-world data. Spend 3-5 hours (not weeks).

4. **Synthesize:** Refine JTBD and persona based on evidence. Note gaps and opportunities.

5. **Ready for next phase:** Move to solution-definition (Working Backwards + Closed World mapping).

## Complete Examples

**For inspiration and patterns:** Read `references/example-outputs.md` for three complete worked examples with globally diverse personas:
- Mobile micro-lending service (Nigeria - market trader)
- Remote team collaboration platform (Singapore - engineering manager with distributed Southeast Asia team)
- Affordable home solar system (Rural India - shopkeeper)

Each example shows the complete flow from JTBD through persona to evidence gathering with cultural context and local insights.

## Output Format

Structure your discovery work as follows:

```markdown
# Customer Discovery: [Problem Space/Opportunity]

## Jobs-to-be-Done Analysis

**Job Statement:**
"When [situation], I want to [functional job], so I can [desired outcome]. 
This helps me [emotional job] and [social job]."

**Functional Jobs:**
- [job 1]
- [job 2]
- [job 3]

**Emotional Jobs:**
- [job 1]
- [job 2]

**Social Jobs:**
- [job 1]
- [job 2]

**Pains (Current Situation):**
- [pain 1 with context]
- [pain 2 with context]
- [pain 3 with context]

**Gains (Desired):**
- [gain 1]
- [gain 2]
- [gain 3]

## Persona: [Name] - [Archetype]

**Profile:**
- Age: [age]
- Occupation: [job]
- Location: [city, country/region]
- Life stage: [situation]

**Context:**
[2-3 sentences describing daily life, responsibilities, current situation, and relevant cultural context]

**Jobs to Be Done:**
**Functional:** [from JTBD above]
**Emotional:** [from JTBD above]
**Social:** [from JTBD above]

**Goals & Motivations:**
- [goal 1]
- [goal 2]
- [goal 3]

**Pain Points & Challenges:**
- [specific pain 1 with local context]
- [specific pain 2 with local context]
- [specific pain 3 with local context]

**Behaviors:**
- **Decision-making:** [individual/family/community]
- **Information sources:** [where they learn]
- **Technology use:** [comfort level, devices]
- **Payment methods:** [how they pay]

**Quote:**
"[Memorable quote capturing their mindset]"

## Evidence Gathering: [Problem Space]

**Research Questions:**
1. [Validation question]
2. [Discovery question]
3. [Solution landscape question]

**Sources Used:**
- [Source 1 with sample size]
- [Source 2 with sample size]
- [Source 3 with sample size]

**Key Findings:**

### Validation
**Confirms:**
- [Finding 1 with evidence]
- [Finding 2 with evidence]

**Contradicts:**
- [Surprising finding 1]
- [Surprising finding 2]

### Landscape
**Existing Solutions:**
- [Solution 1: strengths, weaknesses, pricing]
- [Solution 2: strengths, weaknesses, pricing]

**Gaps & Opportunities:**
- [Unmet need 1]
- [Underserved segment 1]

### Customer Voice
**Key Quotes:**
- "[Direct customer quote 1]"
- "[Direct customer quote 2]"

**Pain Intensity:**
- Frequency: [How often]
- Severity: [Impact]
- Current coping: [What they do today]

**Willingness to Pay:**
- [Price signals from research]

### Trends & Context
**Enabling Factors:**
- [What makes this possible now]

**Headwinds:**
- [Challenges to consider]

**Implications for Solution:**
[3-5 key insights that should inform solution direction]
```

## Tips for Success

**JTBD Tips:**
- Focus on the job, not product features
- All three job types matter—don't skip emotional and social
- Be specific: "30-minute commute" beats "fast transportation"
- Pains are as valuable as gains for innovation

**Persona Tips:**
- **ALWAYS create globally diverse personas** - actively resist Western/US defaults
- Make them realistic and specific with cultural context
- Include local constraints: payment methods, infrastructure, social dynamics
- Use authentic names for the region
- Quote should reflect local voice and concerns
- Test: Can the team imagine this person's actual day in their context?

**Evidence Gathering Tips:**
- Set time limit: 3-5 hours of research, then synthesize
- Look for patterns across multiple sources
- Include evidence from target markets, not just Western sources
- Capture customer language and direct quotes
- Note contradictions—they reveal complexity
- Balance online and offline evidence in emerging markets

## Common Pitfalls

Avoid these mistakes:
- **Western bias:** Defaulting to US/Western Europe personas and contexts
- **Skipping evidence:** Relying only on assumptions without validation
- **Generic personas:** "Tech-savvy millennial" is useless; "Chidinma, 34, market trader in Lagos" is useful
- **Ignoring emotional/social jobs:** These often drive decisions more than functional
- **Analysis paralysis:** Don't spend weeks researching—3-5 hours is enough
- **Confirmation bias:** Actively seek contradicting evidence
- **Jumping to solutions:** Resist urge to define product before understanding problem

## Global Diversity Requirements

**This is critical:** Unless the product/service is explicitly limited to a specific region, you MUST create globally diverse personas across different projects.

**Rotate through:**
- Asia-Pacific (India, China, Japan, Southeast Asia, Australia)
- Africa (Nigeria, Kenya, South Africa, Egypt)
- Latin America (Brazil, Mexico, Argentina, Colombia)
- Middle East (UAE, Saudi Arabia, Turkey, Israel)
- Europe (UK, Germany, Poland, Spain, Nordics)
- North America (US, Canada) - when relevant

**Consider local context:**
- Infrastructure (internet, power, logistics)
- Payment systems (mobile money, cash, local apps)
- Cultural values (individualism vs. collectivism, family dynamics)
- Economic factors (income levels, price sensitivity)
- Language and literacy
- Regulatory environment

See `references/persona-template.md` for detailed global diversity guidelines and examples.

## Next Steps

After completing customer discovery:
1. **Review and validate:** Share with team, test with real customers in target markets
2. **Solution definition:** Use solution-definition skill (Working Backwards + Closed World mapping)
3. **Ideation:** Generate solution ideas using ideation-powerhouse skill
4. **Evaluation & validation:** Rate ideas and deep-dive with critical thinking

This customer understanding is the foundation for all subsequent innovation work. Invest time here—it pays off exponentially.
