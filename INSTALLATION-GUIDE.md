# Installation & Usage Guide

## Innovation Skills Suite

You now have 12 skills across 5 phases of systematic innovation:

**Phase 1:** customer-discovery
**Phase 2:** solution-definition
**Phase 3:** ideation-scamper + 7 SCAMPER technique skills
**Phase 4:** idea-evaluation
**Phase 5:** critical-validation

---

## Installation

### For Claude Code (Recommended)

Skills are structured as SKILL.md files in directories. To use with Claude Code:

**Option 1: Direct Directory Access**
- Skills are already in the repository structure
- Claude Code should be able to access them from: `/Users/amirelion/Documents/Development/innovation-skills/[skill-name]/`
- Each skill has a SKILL.md file that Claude Code reads

**Option 2: Package Skills (If Invocation Not Working)**

If direct invocation doesn't work, you may need to package skills:

1. Create `.claude/skills/` directory in your project:
   ```bash
   mkdir -p .claude/skills
   ```

2. Copy skill directories to `.claude/skills/`:
   ```bash
   cp -r customer-discovery .claude/skills/
   cp -r solution-definition .claude/skills/
   cp -r ideation-scamper .claude/skills/
   # ... repeat for all skills
   ```

3. Reload Claude Code or restart

**Skill Packaging Script (Create if needed):**

```bash
#!/bin/bash
# package-skills.sh - Package innovation skills for Claude Code

SKILLS_DIR=".claude/skills"
mkdir -p $SKILLS_DIR

# List of skills to package
SKILLS=(
  "customer-discovery"
  "solution-definition"
  "ideation-scamper"
  "scamper-substitute"
  "scamper-combine"
  "scamper-adapt"
  "scamper-modify"
  "scamper-put-to-other-uses"
  "scamper-eliminate"
  "scamper-reverse"
  "idea-evaluation"
  "critical-validation"
)

for skill in "${SKILLS[@]}"; do
  echo "Packaging $skill..."
  cp -r "$skill" "$SKILLS_DIR/"
done

echo "All skills packaged to $SKILLS_DIR"
```

Make executable: `chmod +x package-skills.sh`

### For Claude.ai (Alternative)

If you want to use these skills with Claude.ai web interface:

1. Each skill folder needs to be zipped individually
2. Upload via Settings → Skills → Upload Skill
3. Note: Currently skills are designed for Claude Code, so some features may not work in web UI

---

## Usage: The Complete Flow

### Phase 1: customer-discovery

**When to use:**
- Starting a new innovation project
- Validating a problem/opportunity
- Need to understand customer needs deeply

**How to start:**
```
I'm exploring [problem space/opportunity].
Help me do customer-discovery to understand the customer needs.
```

**What Claude will do:**
1. Guide you through Jobs-to-be-Done analysis
2. Create a globally diverse persona with cultural context
3. Help you gather and synthesize evidence

**Output:** Complete customer understanding document with JTBD, persona, and evidence

**Time:** 1-2 hours with Claude's guidance

---

### Phase 2: solution-definition

**When to use:**
- After completing customer-discovery
- Ready to define what you'll build
- Need to align team on solution vision

**How to start:**
```
I've completed customer-discovery for [problem space].
[Paste or reference the customer-discovery output]

Now help me do solution-definition using Working Backwards and Closed World.
```

**What Claude will do:**
1. Help you write a compelling PRFAQ (press release + FAQ)
2. Map the Closed World components of your solution
3. Identify relationships and innovation opportunities

**Output:** Complete solution vision (PRFAQ) + resource inventory (Closed World)

**Time:** 1-2 hours with Claude's guidance

---

## Example Prompts

### Starting customer-discovery

**Prompt 1 (from scratch):**
```
I want to understand the needs of small business owners in Southeast Asia 
who struggle with managing distributed teams. Help me do customer-discovery.
```

**Prompt 2 (with context):**
```
I'm exploring the problem of unreliable electricity in rural areas of developing 
countries. I've done some initial research but need structured customer-discovery. 
Help me with JTBD, persona (make sure it's globally diverse), and evidence gathering.
```

---

### Moving to solution-definition

**After customer-discovery is complete:**

```
Great! Now I have a clear understanding of the customer needs. Let's move to 
solution-definition. Help me write a Working Backwards PRFAQ for a solution 
that addresses these needs, then map the Closed World.
```

**With PRFAQ drafted:**
```
I've written a draft PRFAQ for my solution. Can you review it using the Working 
Backwards framework and help me refine it? Then we'll map the Closed World.

[Paste draft PRFAQ]
```

---

## Key Reminders

### For customer-discovery:

✅ **Always request global diversity:** "Create a globally diverse persona, not US-focused"  
✅ **Allocate 3-5 hours for evidence gathering:** Don't skip this step  
✅ **Use persona voice:** Customer quotes should sound authentic

### For solution-definition:

✅ **PRFAQ first, then Closed World:** Don't map components until vision is clear  
✅ **Iterate the PRFAQ 3-5 times:** First draft is never good enough  
✅ **Be honest in FAQ:** If hard problems are unsolvable, better to know now

---

## What Each Skill Knows

### customer-discovery knows:

- Jobs-to-be-Done framework (functional, emotional, social jobs)
- How to create globally diverse, culturally-grounded personas
- 5 evidence sources and how to synthesize findings
- 3 complete examples from Nigeria, Singapore/SE Asia, India

### solution-definition knows:

- Amazon's Working Backwards PRFAQ methodology
- How to write compelling press releases and FAQs
- Systematic Inventive Thinking's Closed World principle
- How to map internal and external components
- 3 complete examples with PRFAQs and Closed World maps

---

## Troubleshooting

**Q: Skill isn't activating**  
A: Explicitly say "Use the customer-discovery skill" or "Use the solution-definition skill"

**Q: Persona is too Western/US-focused**  
A: Say "Create a globally diverse persona - choose a region outside North America/Europe"

**Q: Not getting evidence gathering**  
A: Say "Help me with evidence gathering step using social media, market research, etc."

**Q: PRFAQ feels like feature list**  
A: Say "Focus on customer benefits and experience, not technical features"

**Q: Closed World has too many/few components**  
A: Aim for 8-15 internal, 5-10 external. Say "Let's refine the component list"

---

## Next Steps After Both Skills

Once you have:
- ✅ Customer understanding (JTBD, persona, evidence)
- ✅ Solution vision (PRFAQ)
- ✅ Resource inventory (Closed World)

You're ready for:
- **Ideation:** Generate innovative ideas using SCAMPER (next skill to build)
- **Evaluation:** Rate and select best ideas
- **Validation:** Deep-dive with Six Hats thinking
- **Technical problem-solving:** TRIZ for hard challenges

---

## Files & Resources

📦 [customer-discovery.zip](computer:///mnt/user-data/outputs/customer-discovery.zip) - Install this first  
📦 [solution-definition.zip](computer:///mnt/user-data/outputs/solution-definition.zip) - Install this second  
📄 [Complete Summary](computer:///mnt/user-data/outputs/UPDATED-SKILLS-SUMMARY.md) - What changed and why  

---

## Quick Start: Try It Now

**30-minute test:**

1. Pick a problem space you're interested in
2. Ask Claude: "Help me do customer-discovery for [problem space]"
3. Go through JTBD, persona (check if it's globally diverse!), and evidence gathering
4. Then: "Now help me do solution-definition using Working Backwards"
5. Write PRFAQ and map Closed World

You'll have a complete customer understanding and solution vision in 30-60 minutes!

---

## Questions?

Both skills include:
- Detailed methodology references
- Complete worked examples
- Templates for outputs
- Tips and common pitfalls

Just ask Claude to read the relevant reference file if you need more detail on any framework.
