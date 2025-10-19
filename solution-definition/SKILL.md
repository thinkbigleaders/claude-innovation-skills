---
name: solution-definition
description: Define clear solution vision through Amazon's Working Backwards methodology (press release + FAQ), then map available resources with Systematic Inventive Thinking's Closed World principle. Use after customer-discovery to bridge from customer needs to concrete solution direction before ideation. Second phase of systematic innovation.
---

# Solution Definition: From Customer Needs to Solution Vision

## Purpose

Bridge from deep customer understanding (Jobs-to-be-Done, persona, evidence) to a clear, compelling solution vision. Use Amazon's Working Backwards to define what you're building and why it matters, then use Closed World mapping to identify all available resources and components for innovation.

## When to Use This Skill

Use this skill when:
- You've completed customer-discovery (JTBD, persona, evidence gathering)
- You need to define what solution to build before detailed ideation
- You want to test if a product vision is compelling before investing in development
- You need to align team and stakeholders on solution direction
- You're ready to identify the specific system you'll innovate within

## Execution Modes

Choose your preferred working mode:

### Interactive Mode (Recommended)

Claude will guide you through PRFAQ creation iteratively, then pause for approval before moving to Closed World mapping.

**Checkpoints:**
1. After PRFAQ draft → Review, iterate 3-5 times until solid
2. After PRFAQ approval → Proceed to Closed World mapping
3. After Closed World → Review final solution definition

**Use when:**
- First time using Working Backwards framework
- Want to iterate on PRFAQ quality
- Need to refine vision before mapping resources
- Prefer step-by-step guidance

### Autonomous Mode

Claude will generate complete PRFAQ + Closed World in one pass, then present for your review.

**Use when:**
- Familiar with PRFAQ and Closed World frameworks
- Want fast first draft to iterate on
- Clear vision of solution already
- Prefer batch review

**To activate:**
```
Use solution-definition skill in interactive mode.
[Paste customer-discovery outputs]
```

---

## Two-Step Process

### Step 1: Working Backwards (Define Solution Vision)

Use Amazon's methodology to define the customer experience you want to create.

**Write a Press Release** as if announcing the product on launch day:
- **Heading:** Product name and one-sentence description
- **Subheading:** Who it's for and core benefit
- **Problem:** Customer pain described vividly (from discovery)
- **Solution:** What it is and how it solves the pain
- **Customer Quote:** Delighted customer in persona's voice
- **How to Get Started:** Onboarding experience
- **Closing:** Vision of what becomes possible

**Write an FAQ** that answers hard questions:
- **Customer FAQs** (who, what, cost, how to get it, guarantees)
- **Stakeholder FAQs** (why now, hard problems, what we're not doing, success metrics, competitive advantages)

**Note on Customer Testimonials:** The press release includes a customer testimonial that should follow a specific anatomy: frustration before the solution → discovery → key benefits → one delightful moment → how it changed their reality → optional advocacy. See `working-backwards.md` for detailed structure.

**Output:** PRFAQ document that makes the value clear and tests if the vision is compelling.

**For detailed methodology:** Read `references/working-backwards.md` for structure, templates, and examples.

### Step 2: Closed World Mapping (Identify Available Resources)

Map all components available within the solution system and its immediate environment using Systematic Inventive Thinking principles.

**Map two types of components:**
1. **Internal components:** Physical parts, materials, features that ARE the product/system (8-15 components)
2. **External components:** Environmental elements, users, inputs/outputs that regularly INTERACT with the system (5-10 components)

**Define relationships:** Note key connections, dependencies, and constraints between components.

**Output:** Complete inventory of resources available for innovation within the defined solution.

**For detailed methodology:** Read `references/closed-world-guide.md` for identification questions, boundaries, and examples.

## Workflow

Follow these steps in sequence:

1. **Review customer discovery:** Have JTBD, persona, and evidence findings ready. These inform your PRFAQ.

2. **Write Press Release:** Start with problem (from customer pains), define solution that addresses the job, write customer quote in persona's authentic voice.

3. **Refine until compelling:** If the press release doesn't make you think "I want that!", iterate. Should take 3-5 drafts.

4. **Write FAQ:** Answer hard questions honestly. This forces thinking through feasibility, economics, strategy.

5. **Get feedback:** Share PRFAQ with stakeholders, potential customers. Listen for confusion, excitement, skepticism.

6. **Iterate PRFAQ:** Refine based on feedback. It's a living document.

7. **Map Closed World:** Now that solution is defined, map all components within and around it.

8. **Note relationships:** Identify key connections and constraints—these reveal innovation opportunities.

9. **Ready for ideation:** Use the Closed World as foundation for generating innovative ideas.

## Complete Examples

**For inspiration and patterns:** Read `references/example-outputs.md` for four complete worked examples:
- Mobile micro-lending service (Nigeria) - FairCredit
- Remote team collaboration platform (Southeast Asia) - AsyncFlow
- Affordable home solar system (Rural India) - SolarSeva
- Disaster-resilient logistics tracker (Sweden) - Unbroken

Each example shows full PRFAQ with detailed customer testimonials followed by Closed World mapping for the same solution.

## Output Format

Structure your solution definition as follows:

```markdown
# Solution Definition: [Product/Service Name]

## PRESS RELEASE: [Product Name]

### Heading
[Product Name]: [One-sentence description]

### Subheading
[Product] helps [customer] [achieve benefit]

### Problem
[2-3 sentences describing customer pain vividly from discovery]

### Solution
[2-3 sentences explaining what it is and how it solves the pain]

### Customer Quote
"[Authentic quote from delighted customer using persona voice]"
- [Customer Name from persona, Location/Context]

### How to Get Started
[2-3 sentences on onboarding experience]

### Closing
[2-3 sentences on vision and what becomes possible]

---

## FAQ

### Customer FAQs

**Q: Who is this for?**
A: [Primary segment, use cases, who it's NOT for]

**Q: What are the key features/benefits?**
A: [3-5 core features with benefits]

**Q: How much does it cost?**
A: [Pricing model, comparison to alternatives, value justification]

**Q: How do I get it?**
A: [Availability, purchase/signup process, time to value]

**Q: What if it doesn't work for me?**
A: [Guarantees, trial periods, support available]

### Stakeholder FAQs

**Q: Why now?**
A: [Technology enablers, market timing, trends from evidence]

**Q: What are the hard problems to solve?**
A: [Technical, operational, GTM challenges]

**Q: What are we NOT doing?**
A: [Scope boundaries, features deliberately excluded]

**Q: How will we measure success?**
A: [Key metrics, success criteria in 6 months, 1 year, 3 years]

**Q: Why will customers choose us?**
A: [Competitive advantages, moats, defensibility]

---

## Closed World Map: [Product/Service Name]

**System Definition:**
[Brief description of the system you're analyzing]

**Internal Components:**
1. [Component] - [function/properties]
2. [Component] - [function/properties]
...
[8-15 total]

**External Components:**
1. [Component] - [presence/role]
2. [Component] - [presence/role]
...
[5-10 total]

**Key Relationships:**
- [Notable interaction or dependency]
- [Notable interaction or dependency]
- [Innovation opportunity or constraint]
```

## Tips for Success

**Working Backwards Tips:**
- Write press release first—if it's not compelling, the product won't be
- Use customer language from discovery, not jargon
- Customer quote should sound like persona's authentic voice
- FAQ "why now?" should reference trends from evidence gathering
- Be honest in FAQ about hard problems—better to know now than later
- Iterate 3-5 times—first draft is never good enough

**Closed World Tips:**
- Only map components after PRFAQ is done—need to know what system you're mapping
- Be systematic—work through product structure methodically
- Internal = IS the product; External = INTERACTS with product
- Include "obvious" components (air, user's hands, network)—they're valuable resources
- Aim for 8-15 internal, 5-10 external—not too few, not too many
- Relationships reveal innovation opportunities and constraints

## Common Pitfalls

Avoid these mistakes:
- **Skipping customer discovery:** PRFAQ will be based on assumptions, not customer reality
- **Feature lists instead of benefits:** Press release should focus on customer experience, not technical specs
- **Vague problem statement:** "People want better X" isn't compelling—make pain vivid
- **Unrealistic FAQ answers:** If FAQ reveals product is impossible/uneconomical, that's valuable learning
- **Adding new components:** Closed World principle is to work with what exists
- **Mapping before vision is clear:** Can't map the Closed World until you know what system you're building

## Integration with Customer Discovery

Solution Definition builds directly on customer-discovery outputs:

**From JTBD:**
- Problem statement comes from pains
- Solution addresses functional, emotional, social jobs
- Gains inform benefits and features

**From Persona:**
- Customer quote in persona's authentic voice
- Context and language match persona's reality
- Onboarding designed for persona's capabilities

**From Evidence:**
- "Why now?" informed by trends and enablers from evidence
- Competitive advantages address gaps identified in landscape
- Pricing informed by willingness to pay research
- Hard problems informed by what exists/doesn't work

## Next Steps

After completing solution definition:
1. **Validate PRFAQ:** Share with stakeholders and potential customers in target markets
2. **Ideation:** Use ideation-powerhouse skill to generate innovative ideas within the Closed World
3. **Technical planning:** If hard problems identified in FAQ are significant, may need technical-breakthrough skill (TRIZ)
4. **Evaluation:** Rate generated ideas against PRFAQ vision and customer jobs

The PRFAQ becomes the north star for the project. The Closed World becomes the foundation for creative ideation.
