# Innovation Skills Suite - Development Handoff

## Project Overview

Building a comprehensive suite of Claude Code skills based on systematic innovation methodology from the "Innovating with ChatGPT" Udemy course. These skills guide users through the complete innovation journey from customer discovery to technical problem-solving.

**Repository:** https://github.com/amirelion/innovation-skills.git

---

## Current Status: Phase 1-2 Complete ✅

### Completed Skills (2/6)

#### 1. **customer-discovery**
**Purpose:** Deep customer understanding before defining solutions

**Three steps:**
1. Jobs-to-be-Done (JTBD) - Functional, emotional, social jobs + pains & gains
2. Persona Creation - Globally diverse, culturally-grounded personas
3. Evidence Gathering - Validate through social media, market research, customer feedback, trends, direct research

**Key Features:**
- ✅ Global diversity requirements (explicit rotation through Asia-Pacific, Africa, Latin America, Middle East, Europe, North America)
- ✅ Evidence gathering framework bridges assumptions to validated understanding
- ✅ 3 complete examples (Nigeria, Singapore, India)
- ✅ Cultural context factors (infrastructure, payment systems, values, language)

**Output:** JTBD + Persona + Evidence → Foundation for solution definition

---

#### 2. **solution-definition**
**Purpose:** Define clear solution vision and map available resources

**Two steps:**
1. Working Backwards - Amazon PRFAQ methodology with enhanced structure
2. Closed World Mapping - SIT principle to map internal and external components

**Key Features:**
- ✅ **7-paragraph press release structure** (Elevator Pitch, Problem, Solution, Leader Quote, Customer Journey, Customer Testimonial, Call to Action)
- ✅ **Customer testimonial anatomy** (7-step pattern: frustration → discovery → benefits → delightful moment → transformation → advocacy)
- ✅ **Stakeholder FAQs** (renamed from Internal FAQs for clarity)
- ✅ **4 diverse examples:**
  - FairCredit (Nigeria, fintech/micro-lending)
  - AsyncFlow (SE Asia, B2B collaboration SaaS)
  - SolarSeva (India, solar energy/infrastructure)
  - Unbroken (Sweden, B2B disaster logistics)
- ✅ **Optional visuals guidance** (UI sketches, storyboards, architecture diagrams)

**Output:** Compelling PRFAQ + Complete resource inventory (Closed World) → Foundation for ideation

---

## Roadmap: Remaining Skills (4/6)

### Phase 3: **ideation-powerhouse** (Next Priority)
**Purpose:** Generate innovative ideas using SCAMPER within Closed World constraints

**Planned Structure:**
- **Main orchestration skill** that manages the ideation process
- **7 individual SCAMPER tools** (can be used standalone or via orchestrator):
  1. **Substitute** - Replace components with alternatives
  2. **Combine** - Merge components in novel ways
  3. **Adapt** - Borrow ideas from other contexts
  4. **Modify/Magnify/Minify** - Change attributes, scale, properties
  5. **Put to other uses** - Repurpose components
  6. **Eliminate** - Remove components to simplify
  7. **Reverse/Rearrange** - Flip or reorder processes/components

**Key Design Decisions:**
- Should it be ONE skill with 7 sections, or 8 skills (1 orchestrator + 7 tools)?
- Recommendation: **8 skills** for flexibility
  - `ideation-scamper` (orchestrator) - guides through all 7 tools systematically
  - `scamper-substitute`, `scamper-combine`, etc. (individual tools) - can use standalone
- Each SCAMPER tool should:
  - Reference the Closed World map from solution-definition
  - Provide question prompts specific to that technique
  - Include 2-3 examples showing technique in action
  - Generate 5-10 ideas per technique

**Estimated Effort:** 8-12 hours
- Orchestrator skill: 2 hours
- Each SCAMPER tool: 1-1.5 hours × 7 = 7-10 hours

**Examples to Include:**
- Apply to FairCredit, AsyncFlow, SolarSeva, Unbroken
- Show how each SCAMPER technique reveals different innovation angles

---

### Phase 4: **idea-evaluation**
**Purpose:** Rate and select ideas based on multiple criteria

**Planned Structure:**
- Multi-criteria evaluation framework
- Criteria categories:
  - Customer value (impact on JTBD, pain relief, gain creation)
  - Feasibility (technical, operational, resource availability)
  - Viability (business model, pricing, economics)
  - Desirability (emotional appeal, brand fit)
  - Strategic fit (competitive advantage, vision alignment)
- Scoring approach: 1-5 scale per criterion
- Weighted scoring (user defines weights based on priorities)
- Output: Ranked list with top 3-5 ideas for deeper validation

**Key Features:**
- Customizable criteria based on context
- Both quantitative (scores) and qualitative (reasoning) evaluation
- Comparison matrix showing trade-offs
- Filter options (minimum thresholds, must-haves)

**Estimated Effort:** 3-4 hours

**Examples:**
- Evaluate 20-30 ideas generated from FairCredit SCAMPER exercise
- Show how different weighting changes ranking

---

### Phase 5: **critical-validation**
**Purpose:** Deep-dive validation of top ideas using Six Thinking Hats sequence

**Planned Structure:**
- **Six Hats Framework:**
  1. **White Hat** - Facts, data, information (what do we know/need to know?)
  2. **Red Hat** - Emotions, intuition, gut feelings (how do we feel?)
  3. **Yellow Hat** - Benefits, optimism, value (what's good about this?)
  4. **Black Hat** - Risks, problems, caution (what could go wrong?)
  5. **Green Hat** - Creativity, alternatives, possibilities (how can we improve?)
  6. **Blue Hat** - Process, meta-thinking, decisions (what's the conclusion?)

- **Recommended sequence for deep validation:**
  1. Red Hat - Initial gut check (proceed if positive energy)
  2. White Hat - Gather facts and fill knowledge gaps
  3. Yellow Hat - Map all benefits and optimistic scenarios
  4. Black Hat - Identify all risks, problems, reasons it might fail
  5. Green Hat - Creative solutions to Black Hat problems
  6. Blue Hat - Synthesize and decide (go/no-go/iterate)
  7. Red Hat - Final emotional check after analysis

**Key Features:**
- Can use all 6 hats or just a subset
- Guided prompts for each hat perspective
- Output template capturing insights from each hat
- Decision framework at end (Blue Hat)

**Estimated Effort:** 4-6 hours
- Framework and orchestration: 2 hours
- Individual hat guidance: 30-45 min × 6 = 3-4 hours

**Examples:**
- Deep-dive on top 3 FairCredit ideas
- Show how Black Hat surfaces risks Yellow Hat missed
- Demonstrate Green Hat solving Black Hat problems

---

### Phase 6: **technical-breakthrough** (As Needed)
**Purpose:** Creative problem-solving for hard technical challenges using TRIZ

**Planned Structure:**
- **TRIZ Overview** - Theory of Inventive Problem Solving
- **40 Inventive Principles** (condensed to top 20 most relevant)
- **Contradiction Matrix** - Physical vs. Technical contradictions
- Key principles to include:
  1. Segmentation
  2. Taking out / Extraction
  3. Local quality
  4. Asymmetry
  5. Merging / Consolidation
  6. Universality
  7. Nested doll / Matryoshka
  8. Dynamics
  9. Partial or excessive action
  10. Preliminary action
  11. Beforehand cushioning
  12. Equipotentiality
  13. The other way round / Inversion
  14. Spheroidality / Curvature
  15. Parameter changes
  16. Phase transitions
  17. Thermal expansion
  18. Feedback
  19. Self-service
  20. Copying / Cheap disposables

**Usage Pattern:**
- Invoked when Black Hat (Phase 5) identifies hard technical problems
- User describes contradiction: "Want X but need Y, and they conflict"
- Skill suggests relevant TRIZ principles
- Examples show how principle solves contradiction

**Estimated Effort:** 6-8 hours (TRIZ is complex)

**Examples:**
- SolarSeva: Need battery storage (expensive) but want affordable pricing
- AsyncFlow: Need real-time feeling but want async-first
- Unbroken: Need constant syncing but internet unavailable

---

## Complete Innovation Journey Flow

```
┌─────────────────────────────┐
│   1. customer-discovery     │
│   • JTBD                    │
│   • Persona (global)        │
│   • Evidence Gathering      │
└──────────┬──────────────────┘
           │
           ↓
┌─────────────────────────────┐
│   2. solution-definition    │
│   • Working Backwards       │
│   • Closed World Mapping    │
└──────────┬──────────────────┘
           │
           ↓
┌─────────────────────────────┐
│   3. ideation-powerhouse    │
│   • SCAMPER (7 techniques)  │
│   • Generate 30-50 ideas    │
└──────────┬──────────────────┘
           │
           ↓
┌─────────────────────────────┐
│   4. idea-evaluation        │
│   • Multi-criteria scoring  │
│   • Rank & filter           │
│   • Top 3-5 ideas           │
└──────────┬──────────────────┘
           │
           ↓
┌─────────────────────────────┐
│   5. critical-validation    │
│   • Six Thinking Hats       │
│   • Deep-dive validation    │
│   • Go/no-go decision       │
└──────────┬──────────────────┘
           │
           ├─(if hard technical problems)─┐
           │                               ↓
           │                    ┌──────────────────────┐
           │                    │ 6. technical-        │
           │                    │    breakthrough      │
           │                    │ • TRIZ principles    │
           │                    │ • Solve              │
           │                    │   contradictions     │
           │                    └──────────────────────┘
           │
           ↓
     [Implementation]
```

---

## Additional Skills Considered (Future)

### From Original Brainstorm

7. **SIT Creative Advertising Templates** (Optional extension)
   - Extreme worth
   - Extreme effort
   - Extreme consequences
   - Pictorial analogy
   - **Decision:** Lower priority - focus on core innovation flow first

---

## Design Principles Across All Skills

### 1. **Global Diversity by Default**
- Examples must rotate through different geographies
- Cultural context always considered
- Avoid Western/US bias

### 2. **Connected Journey**
- Each skill builds on previous outputs
- Clear handoff points between phases
- Consistent example cases across skills (FairCredit, AsyncFlow, SolarSeva, Unbroken)

### 3. **Standalone + Orchestrated**
- Skills work standalone for experienced users
- Can be orchestrated in sequence for complete journey
- Clear entry/exit points

### 4. **Rich Examples**
- Minimum 3-4 complete worked examples per skill
- Diverse domains (B2C/B2B, digital/physical, different industries)
- Show both successful application AND common pitfalls

### 5. **Actionable Templates**
- Every skill includes ready-to-use templates
- Clear output format specifications
- Integration guidance with previous/next phases

---

## Repository Structure

```
innovation-skills/
├── README.md (to be created)
├── HANDOFF.md (this file)
├── INSTALLATION-GUIDE.md
├── UPDATED-SKILLS-SUMMARY.md
├── Working_Backwards_assets/
│   ├── Example PRFAQ - ID-me.pdf
│   ├── PRFAQ breakdown.pdf
│   ├── Unbroken PRFAQ V 1_0.docx
│   └── unbroken.txt
├── customer-discovery/
│   ├── SKILL.md
│   ├── assets/
│   │   └── customer-discovery-template.md
│   └── references/
│       ├── jtbd-framework.md
│       ├── persona-template.md
│       ├── evidence-gathering.md
│       └── example-outputs.md
└── solution-definition/
    ├── SKILL.md
    ├── assets/
    │   └── solution-definition-template.md
    └── references/
        ├── working-backwards.md
        ├── closed-world-guide.md
        └── example-outputs.md

[Future structure:]
├── ideation-scamper/
├── scamper-substitute/
├── scamper-combine/
├── scamper-adapt/
├── scamper-modify/
├── scamper-put-to-other-uses/
├── scamper-eliminate/
├── scamper-reverse/
├── idea-evaluation/
├── critical-validation/
└── technical-breakthrough/
```

---

## Time Estimates

**Completed:** ~7 hours
- customer-discovery: ~4 hours
- solution-definition: ~3 hours (initial) + ~2 hours (enhancements) = ~5 hours
- **Total actual: ~9 hours**

**Remaining:**
- ideation-powerhouse: ~10 hours (orchestrator + 7 SCAMPER skills)
- idea-evaluation: ~4 hours
- critical-validation: ~5 hours
- technical-breakthrough: ~7 hours
- Documentation & polish: ~2 hours
- **Total remaining: ~28 hours**

**Grand total: ~35-40 hours for complete suite**

---

## Next Immediate Steps

1. **Create README.md** for repository overview
2. **Build ideation-powerhouse** (Phase 3)
   - Start with orchestrator skill
   - Build 7 SCAMPER individual skills
   - Create comprehensive examples
3. **Continue through Phases 4-6**
4. **Polish and integrate** across all skills
5. **Create master orchestrator** (optional) that guides through entire journey

---

## Key Decisions to Make

### 1. SCAMPER Structure
**Question:** One skill or eight skills (orchestrator + 7 tools)?

**Recommendation:** 8 skills for maximum flexibility
- `ideation-scamper` - guides systematically through all 7
- Individual tools available for targeted use
- More modular, easier to maintain

### 2. Six Hats Approach
**Question:** All 6 hats mandatory or user selects subset?

**Recommendation:**
- Default sequence: Red → White → Yellow → Black → Green → Blue → Red
- Allow users to skip hats if time-constrained
- Provide "quick validation" path (Red → Yellow → Black → Blue)

### 3. TRIZ Scope
**Question:** All 40 principles or curated subset?

**Recommendation:**
- Start with 20 most applicable principles
- Group by type (structural, temporal, system)
- Can expand to all 40 later based on usage

### 4. Example Continuity
**Question:** Same 4 examples (FairCredit, AsyncFlow, SolarSeva, Unbroken) across all skills?

**Recommendation:** Yes, with flexibility
- Core 4 examples threaded throughout
- Add 1-2 new examples per skill for variety
- Shows complete journey from discovery → validated innovation

---

## Reference Materials

### Course Basis
- Udemy Course: "Build a ChatGPT-Supercharged Product Innovation Machine"
- Instructor: [Your name/course details]

### Methodologies Integrated
1. **Jobs-to-be-Done** (Clayton Christensen)
2. **Persona Development** (Alan Cooper, global diversity emphasis)
3. **Working Backwards** (Amazon PRFAQ methodology)
4. **Closed World** (Systematic Inventive Thinking - SIT)
5. **SCAMPER** (Bob Eberle - creative thinking technique)
6. **Six Thinking Hats** (Edward de Bono - parallel thinking)
7. **TRIZ** (Genrich Altshuller - inventive problem solving)

### Additional Resources
- Working_Backwards_assets/ contains PDFs and examples
- ID-me and Unbroken PRFAQs as reference implementations

---

## Success Metrics

**Skill Quality:**
- Each skill has 3+ complete worked examples
- Clear input/output specifications
- Templates ready for immediate use
- Integration points documented

**Suite Completeness:**
- All 6 core skills implemented
- Consistent structure and quality
- Comprehensive documentation
- Installation guide tested

**Usability:**
- User can complete discovery → validated innovation in 12-20 hours
- Skills work standalone or orchestrated
- Examples cover diverse domains and geographies

---

## Contact & Collaboration

**Repository:** https://github.com/amirelion/innovation-skills.git
**Current Status:** Phase 1-2 complete (2/6 skills)
**Last Updated:** October 2025
**Next Milestone:** Phase 3 - ideation-powerhouse

---

## Notes for Context Compaction

**Key points to retain:**
1. 2 skills complete: customer-discovery, solution-definition
2. 4 skills remaining: ideation-powerhouse (next), idea-evaluation, critical-validation, technical-breakthrough
3. Enhanced Working Backwards with 7-paragraph structure and testimonial anatomy
4. 4 diverse examples: FairCredit (Nigeria), AsyncFlow (SE Asia), SolarSeva (India), Unbroken (Sweden)
5. Global diversity requirement throughout
6. Repository: https://github.com/amirelion/innovation-skills.git
7. Next: Build ideation-powerhouse (SCAMPER orchestrator + 7 individual tools)
8. Total remaining effort: ~28 hours

**What can be dropped:**
- Detailed file contents (all in git)
- PDF specifics (reference files available)
- Intermediate development history
- Detailed structure explanations
