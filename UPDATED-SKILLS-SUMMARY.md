# Innovation Skills: Customer-Discovery & Solution-Definition

## Latest Update: Enhanced Working Backwards (October 2025)

### What's New in This Release

**Solution-Definition Skill Enhancements:**
1. ✨ **7-Paragraph Press Release Structure** - Detailed breakdown with anatomy for each section
2. ✨ **Customer Testimonial Anatomy** - Explicit pattern: frustration → discovery → delight → advocacy
3. ✨ **Elevator Pitch Structure** - Clear elements for the opening paragraph
4. ✨ **Stakeholder FAQ Terminology** - Updated from "Internal FAQs" for clarity
5. ✨ **4th Example Added** - Unbroken (disaster logistics, Sweden) for domain diversity
6. ✨ **Enhanced Testimonials** - All examples now follow detailed anatomy pattern
7. ✨ **Optional Visuals Section** - Guidance on adding UI sketches, journey storyboards, architecture diagrams

---

## Original Development History

### Your Feedback

1. **Diversity Issue:** "Personas should be more diverse. Not just US and not just west coast. More global."
2. **Gap in Flow:** "We jump too quickly from JTBD to closed world. Maybe we will come up with ideas/solutions not in our current product."

### The Solution: Split Into Two Skills

**Original plan:** One "discovery-to-definition" skill (JTBD → Persona → Closed World)

**Problem identified:** Closed World requires knowing WHAT you're building. But often you start with just customer needs.

**New approach:** Two sequential skills:

## Skill #1: customer-discovery

**Purpose:** Understand customer needs deeply before defining solutions

**Three steps:**
1. **Jobs-to-be-Done** - Functional, emotional, social jobs + pains & gains
2. **Persona Creation** - Globally diverse, culturally-grounded personas
3. **Evidence Gathering** - Validate through social media, market research, customer feedback, trends, and direct research

**Output:** Deep understanding of customer needs, validated with real-world evidence

**Global Diversity:** 
- CRITICAL requirement: Rotate through Asia-Pacific, Africa, Latin America, Middle East, Europe, North America
- Explicit guidelines in persona template
- Examples from Nigeria, Singapore, India
- Cultural context requirements (payment systems, infrastructure, family dynamics, language)

[View customer-discovery skill](computer:///mnt/user-data/outputs/customer-discovery.zip)

---

## Skill #2: solution-definition

**Purpose:** Define clear solution vision and map available resources

**Two steps:**
1. **Working Backwards** - Amazon's PRFAQ methodology to define what you're building
   - Press Release: Heading, problem, solution, customer quote, vision
   - FAQ: Customer FAQs (who, what, cost, how) + Internal FAQs (why now, hard problems, not doing, metrics, advantages)
2. **Closed World Mapping** - SIT principle to map internal and external components

**Output:** Compelling vision (PRFAQ) + complete resource inventory (Closed World)

**Why this works:** 
- Working Backwards bridges from customer needs to solution direction
- Closed World then grounds that vision in actual available resources
- Clear sequence: needs → vision → resources → ideation

[View solution-definition skill](computer:///mnt/user-data/outputs/solution-definition.zip)

---

## The Complete Flow

```
┌─────────────────────────┐
│  customer-discovery     │
│  1. Jobs-to-be-Done     │
│  2. Persona (global)    │
│  3. Evidence Gathering  │
└───────────┬─────────────┘
            │
            ↓
┌─────────────────────────┐
│  solution-definition    │
│  1. Working Backwards   │
│  2. Closed World        │
└───────────┬─────────────┘
            │
            ↓
      [ideation-powerhouse]
```

---

## What's Inside Each Skill

### customer-discovery Structure

**SKILL.md** (~10KB)
- Overview of 3-step process
- When to use the skill
- Workflow guidance
- **CRITICAL: Global diversity requirements**
- Tips, pitfalls, output format

**references/** (4 files, ~50KB)
- `jtbd-framework.md` - JTBD methodology
- `persona-template.md` - **WITH EXPLICIT GLOBAL DIVERSITY GUIDELINES**
- `evidence-gathering.md` - **NEW: Research sources and synthesis**
- `example-outputs.md` - **3 globally diverse examples:**
  - Mobile micro-lending (Nigeria - market trader)
  - Remote collaboration (Singapore - distributed Southeast Asia team)
  - Home solar (Rural India - shopkeeper)

**assets/**
- `customer-discovery-template.md` - Ready-to-use template

---

### solution-definition Structure

**SKILL.md** (~9KB)
- Overview of 2-step process  
- When to use (after customer-discovery)
- Workflow guidance
- Integration with customer-discovery
- Tips, pitfalls, output format

**references/** (3 files, ~70KB)
- `working-backwards.md` - **NEW: Amazon PRFAQ methodology**
- `closed-world-guide.md` - SIT Closed World principles
- `example-outputs.md` - **Complete PRFAQs + Closed World for:**
  - FairCredit (Nigerian micro-lending)
  - AsyncFlow (Southeast Asia collaboration)
  - SolarSeva (Rural India solar)

**assets/**
- `solution-definition-template.md` - Ready-to-use PRFAQ + Closed World template

---

## Key Improvements

### 1. Global Diversity (FIXED)

**Before:** Examples were US West Coast-centric

**Now:**
- **Explicit requirement** in SKILL.md and persona-template.md
- **Diverse examples:**
  - Nigeria (Chidinma - Lagos market trader)
  - Singapore/SE Asia (Mei Lin - distributed engineering team)
  - India (Rajesh - rural shopkeeper)
- **Cultural context** included:
  - Local payment methods (mobile money, UPI, cash)
  - Infrastructure realities (power, internet, logistics)
  - Family/community decision-making
  - Language considerations
  - Economic contexts

**Persona template now includes:**
- Geographic diversity requirements
- "Avoid Western Bias" section
- Cultural factors to consider
- Example personas from 4 different regions

### 2. Evidence Gathering (NEW)

**Why it matters:** Bridges from assumptions to validated understanding

**What it includes:**
- 5 evidence sources (social media, market/competitors, customer feedback, tech trends, direct research)
- How to select sources for your context
- Synthesis framework (validation, landscape, customer voice, trends)
- 3-5 hour time-boxed approach (not weeks)
- Integration with JTBD/persona refinement

**In examples:** Each shows complete evidence gathering with findings from Reddit, reviews, interviews, reports

### 3. Working Backwards (NEW)

**Why it matters:** Defines solution direction before jumping to components

**What it includes:**
- Complete PRFAQ structure
- Press release writing guidance
- Customer and internal FAQ templates
- How to refine until compelling
- Integration with customer-discovery outputs

**In examples:** Full press releases and FAQs for all three products

---

## Global Diversity Requirements - Details

### Geographic Rotation

**MUST rotate through:**
- Asia-Pacific: India, China, Japan, SE Asia, Australia
- Africa: Nigeria, Kenya, South Africa, Egypt  
- Latin America: Brazil, Mexico, Argentina, Colombia
- Middle East: UAE, Saudi Arabia, Turkey, Israel
- Europe: UK, Germany, Poland, Spain, Nordics
- North America: US, Canada (when relevant)

### Cultural Context Factors

**Always consider:**
- Infrastructure (internet, power, logistics)
- Payment systems (mobile money, cash, local apps)
- Cultural values (individualism vs collectivism, family dynamics)
- Economic factors (income levels, price sensitivity)
- Language and literacy
- Regulatory environment

### Example Persona Snapshots Provided

1. **Priya Sharma** - Pune, India micro-entrepreneur
2. **Carlos Mendoza** - Mexico City multi-job hustler
3. **Amina Hassan** - Nairobi connected professional
4. **Kenji Tanaka** - Osaka efficiency-focused salaryman

These show HOW to create culturally-grounded, globally diverse personas.

---

## Updated Innovation Journey

### Phase 1: customer-discovery
**Input:** Problem space or opportunity area  
**Output:** JTBD + Persona + Evidence  
**Time:** 4-8 hours

### Phase 2: solution-definition  
**Input:** Customer-discovery outputs  
**Output:** PRFAQ + Closed World  
**Time:** 3-6 hours

### Phase 3: ideation-powerhouse (NEXT TO BUILD)
**Input:** PRFAQ vision + Closed World resources  
**Output:** Innovative ideas using SCAMPER  
**Time:** 2-4 hours

### Phase 4: idea-evaluation
**Input:** Generated ideas  
**Output:** Rated and prioritized ideas  
**Time:** 1-2 hours

### Phase 5: critical-validation
**Input:** Top ideas  
**Output:** Deep-dive validation via Six Hats  
**Time:** 2-3 hours

### Phase 6: technical-breakthrough (as needed)
**Input:** Hard technical challenges  
**Output:** Creative solutions via TRIZ  
**Time:** Variable

---

## Files Delivered

✅ [customer-discovery.zip](computer:///mnt/user-data/outputs/customer-discovery.zip)
✅ [solution-definition.zip](computer:///mnt/user-data/outputs/solution-definition.zip)

---

## What You Should Do Next

### 1. Review & Test

**customer-discovery:**
- Check global diversity guidelines - is this comprehensive enough?
- Review example personas (Nigeria, Singapore, India) - authentic?
- Test evidence gathering framework on a real project

**solution-definition:**
- Review Working Backwards methodology - clear enough?
- Check example PRFAQs - compelling vision?
- Test the sequence: discovery → PRFAQ → Closed World

### 2. Provide Feedback

**Questions for you:**
1. Are the global diversity requirements clear and comprehensive?
2. Does evidence gathering framework cover the right sources?
3. Is Working Backwards methodology detailed enough?
4. Does the flow (discovery → definition → ideation) make sense now?
5. Any adjustments needed before we build remaining skills?

### 3. Next Skills to Build

Remaining 4 skills in the journey:

3. **ideation-powerhouse** - SCAMPER orchestration with all 7 tools
4. **idea-evaluation** - Multi-criteria rating and selection  
5. **critical-validation** - Six Hats sequence (red→white→yellow→black+green→blue→red)
6. **technical-breakthrough** - TRIZ for difficult technical problems

---

## Time Investment

**Completed:**
- customer-discovery: ~4 hours
- solution-definition: ~3 hours
- **Total so far: ~7 hours**

**Remaining:**
- 4 skills × 3-4 hours each = 12-16 hours
- **Total for complete suite: ~20-25 hours**

---

## Key Takeaways

✅ **Fixed diversity issue** - Explicit global requirements, diverse examples, cultural context  
✅ **Fixed flow gap** - Added evidence gathering and Working Backwards bridge  
✅ **Better structure** - Split into logical phases: understand → define → ideate  
✅ **Comprehensive** - Each skill has frameworks, examples, templates  

Ready to proceed with **ideation-powerhouse** or want to test these first?

---

## Latest Enhancements Summary

### Files Updated in Solution-Definition Skill

**`working-backwards.md`** (~60% larger):
- Added 7-paragraph press release structure with detailed anatomy for each paragraph
- Added comprehensive customer testimonial anatomy section
- Added elevator pitch structure and elements
- Updated terminology from "Internal FAQs" to "Stakeholder FAQs"
- Added optional visuals section (UI sketches, storyboards, architecture diagrams)
- Integrated ID-me examples throughout for illustration
- Enhanced output template to reflect 7-paragraph structure

**`example-outputs.md`** (~30% larger):
- Enhanced all three existing customer testimonials to follow detailed anatomy
- Added complete 4th example: Unbroken (disaster-resilient logistics, Sweden)
- Updated all FAQ terminology from "Internal" to "Stakeholder"
- Now includes 4 diverse examples across geographies and domains:
  - FairCredit (Nigeria, fintech/informal economy)
  - AsyncFlow (Southeast Asia, B2B SaaS)
  - SolarSeva (India, energy/infrastructure)
  - Unbroken (Sweden, B2B logistics/disaster management)

**`SKILL.md`**:
- Updated FAQ terminology to "Stakeholder FAQs"
- Added note about customer testimonial structure and anatomy
- Updated examples count from 3 to 4
- Added reference to enhanced testimonials in examples

### What Users Get

✅ **Comprehensive PRFAQ methodology** matching professional standards
✅ **Clear testimonial structure** for creating authentic customer voices
✅ **4 diverse examples** across continents, industries, and business models
✅ **Updated terminology** consistent with business practice
✅ **Optional visuals guidance** for enhanced communication

### Git Repository

📂 **GitHub:** https://github.com/amirelion/innovation-skills.git
📦 **Status:** Local updates complete, ready for commit and push

---

## Next Steps

1. **Test the enhanced skills** on a real project
2. **Provide feedback** on the new structure and examples
3. **Proceed with next skill:** ideation-powerhouse (SCAMPER tools)
4. **Git workflow:** Commit and push when ready
