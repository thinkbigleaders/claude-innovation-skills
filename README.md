# Claude Innovation Skills

A curated collection of AI-powered skills for systematic innovation, from customer discovery to critical validation. These skills help you build better products by following proven methodologies like Jobs-to-be-Done, Working Backwards (PRFAQ), SCAMPER, and Six Thinking Hats.

## Overview

This repository contains ready-to-use Claude skills that guide you through the innovation process:

1. **Customer Discovery** - Understand customer needs through JTBD analysis and persona creation
2. **Solution Definition** - Define solutions using Amazon's Working Backwards (PRFAQ) methodology
3. **Ideation (SCAMPER)** - Generate creative ideas using the SCAMPER framework
4. **Idea Evaluation** - Evaluate ideas with multi-criteria scoring
5. **Critical Validation** - Validate ideas using Six Thinking Hats methodology

## Available Skills

### Phase 1: Customer Discovery
- **customer-discovery** - Deep customer understanding through Jobs-to-be-Done analysis, globally diverse persona creation, and evidence gathering

### Phase 2: Solution Definition
- **solution-definition** - Working Backwards (PRFAQ) methodology with Closed World mapping
- **prfaq-writer** - Amazon-style Press Release FAQ writer for solution definition

### Phase 3: Ideation
- **ideation-scamper** - Complete SCAMPER ideation framework (all 7 techniques)
- **scamper-substitute** - Generate ideas by substituting components
- **scamper-combine** - Create innovations by combining elements
- **scamper-adapt** - Adapt existing solutions to new contexts
- **scamper-modify** - Modify and magnify existing solutions
- **scamper-put-to-other-uses** - Find new uses for existing solutions
- **scamper-eliminate** - Simplify by removing elements
- **scamper-reverse** - Reverse or rearrange processes

### Phase 4: Evaluation
- **idea-evaluation** - Multi-criteria scoring framework for evaluating ideas

### Phase 5: Validation
- **critical-validation** - Six Thinking Hats methodology for critical thinking and validation

## What are Claude Skills?

Claude Skills are reusable prompt templates that help Claude assist you with specific tasks. They provide structured guidance and proven methodologies to help you innovate systematically.

Learn more: [What are Skills? - Claude Help Center](https://support.claude.com/en/articles/12512176-what-are-skills)

## Requirements

**⚠️ Skills require a paid Claude account** (Pro, Max, Team, or Enterprise plan). As of November 2025, skills are not available on the free plan.

Additionally:
- **Code execution** must be enabled in your account settings
- **Enterprise/Team users**: Your administrator must enable "Code execution and file creation" and "Skills" in Admin settings
- Each user must upload skills individually (they are private to your account)

## Quick Start

### For Non-Technical Users (Easiest Method)

1. **Download a skill file**
   - Go to the [.skill-files](/.skill-files) folder
   - Download the `.skill` file for the skill you want to use
   - Save it to your computer

2. **Upload and enable the skill in Claude**
   - Log in to [Claude.ai](https://claude.ai) with your Pro, Max, Team, or Enterprise account
   - Navigate to **Settings** → **Capabilities**
   - Ensure **"Code execution and file creation"** is enabled
   - Scroll to the **Skills** section
   - Click **"Upload skill"** and upload the ZIP file containing your skill folder
   - Toggle the skill on or off as needed

3. **Use the skill**
   - Start a new conversation or use an existing one
   - Type `/` in the chat to see all available skills
   - Select your uploaded skill from the list
   - Follow the prompts Claude provides

**For detailed instructions on enabling and using skills**: [How to enable Skills - Claude Help Center](https://support.claude.com/en/articles/12512180-using-skills-in-claude)

### For Developers (Clone the Repository)

1. **Clone this repository**
   ```bash
   git clone https://github.com/thinkbigleaders/claude-innovation-skills.git
   cd claude-innovation-skills
   ```

2. **Copy skills to your Claude project**
   ```bash
   # Copy the skill folder to your project's .claude/skills/ directory
   cp -r customer-discovery ~/.claude/skills/
   ```

3. **Use in Claude Code or Claude.ai**
   - The skill will be automatically available
   - Use `/skill-name` to activate it

### Manual Installation (For Any Skill)

1. Navigate to the skill folder you want to use (e.g., `customer-discovery/`)
2. Copy the entire folder to your Claude skills directory:
   - **macOS/Linux**: `~/.claude/skills/`
   - **Windows**: `%USERPROFILE%\.claude\skills\`
3. The skill is now available in Claude!

## How to Use Skills

Each skill operates in two modes:

### Interactive Mode (Recommended for First-Timers)
Claude guides you step-by-step, asking for approval at key checkpoints.

**Example:**
```
Use customer-discovery in interactive mode for a new fitness app
```

### Autonomous Mode (For Experienced Users)
Claude generates complete outputs based on your initial prompt.

**Example:**
```
Use customer-discovery in autonomous mode for a new fitness app
```

## Skill Structure

Each skill folder contains:

```
skill-name/
├── SKILL.md                    # Main skill file with full methodology
├── assets/                     # Templates and worksheets
│   └── template.md
├── quick-reference/            # Quick reference guides
│   └── quick-reference.md
└── references/                 # Detailed frameworks and examples
    ├── framework.md
    └── example-outputs.md
```

## Contributing

We welcome contributions! Whether you want to:
- Add a new innovation skill
- Improve existing skills
- Fix bugs or typos
- Add examples or documentation

Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to submit your contributions.

## Innovation Workflow

Use these skills in sequence for a complete innovation process:

```
1. Customer Discovery
   ↓
2. Solution Definition (PRFAQ)
   ↓
3. Ideation (SCAMPER)
   ↓
4. Idea Evaluation
   ↓
5. Critical Validation (Six Hats)
```

## Examples

### Example 1: Customer Discovery for FinTech
```
Use customer-discovery in interactive mode for a micro-lending platform
targeting small business owners in Nigeria
```

### Example 2: PRFAQ for SaaS
```
Use prfaq-writer to create a Press Release FAQ for an async collaboration
tool for distributed teams in Southeast Asia
```

### Example 3: SCAMPER Ideation
```
Use ideation-scamper to generate ideas for improving our customer onboarding
process using all 7 SCAMPER techniques
```

## Resources

- **Quick References**: Each skill has a `quick-reference/` folder with condensed guides
- **Example Outputs**: Check `references/example-outputs.md` in each skill for real-world examples
- **PRFAQ Resources**: The `prfaq-writer/useful-files/` folder contains reference materials, examples, and templates for the Working Backwards methodology

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

You are free to use, modify, and share these skills in your innovation projects!

## Support

- **Issues**: [Report bugs or request features](https://github.com/thinkbigleaders/claude-innovation-skills/issues)
- **Discussions**: [Join the conversation](https://github.com/thinkbigleaders/claude-innovation-skills/discussions)

## Credits

Created and maintained by the Think Big Leaders community. Built on proven methodologies:
- Jobs-to-be-Done (Clayton Christensen)
- Working Backwards / PRFAQ (Amazon)
- SCAMPER (Bob Eberle)
- Six Thinking Hats (Edward de Bono)

---

**Ready to innovate?** Start with [customer-discovery](./.skill-files/customer-discovery.skill) to understand your customers deeply!
