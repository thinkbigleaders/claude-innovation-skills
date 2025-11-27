# Contributing to Claude Innovation Skills

Thank you for your interest in contributing to the Claude Innovation Skills repository! We welcome contributions from the community to make this resource even better.

## How to Contribute

There are several ways you can contribute:

1. **Add a new innovation skill**
2. **Improve existing skills**
3. **Fix bugs or typos**
4. **Add examples and documentation**
5. **Share feedback and suggestions**

## Adding a New Skill

### Before You Start

1. Check if a similar skill already exists
2. Ensure your skill follows a proven innovation methodology
3. Make sure it fits within the innovation workflow (Discovery → Definition → Ideation → Evaluation → Validation)

### Skill Structure

Every skill should follow this folder structure:

```
your-skill-name/
├── SKILL.md                    # Main skill file (required)
├── assets/                     # Templates and worksheets
│   └── template.md
├── quick-reference/            # Quick reference guides
│   └── quick-reference.md
└── references/                 # Detailed frameworks and examples
    ├── framework.md
    └── example-outputs.md
```

### SKILL.md Format

Your `SKILL.md` file should include:

```markdown
---
name: your-skill-name
description: Brief description of what the skill does and when to use it
---

# Skill Title

## Purpose

Explain the purpose of this skill and what outcomes it delivers.

## When to Use This Skill

- Bullet points explaining when to use
- What problems it solves
- Where it fits in the innovation process

## Execution Modes

### Interactive Mode (Recommended for First-Timers)
[Explain how interactive mode works]

### Autonomous Mode (For Experienced Users)
[Explain how autonomous mode works]

## Core Framework

[Explain the methodology/framework the skill uses]

## Step-by-Step Guide

[Detailed instructions for using the skill]

## Examples

[Provide 2-3 diverse examples]

## Quick Reference

[Link to quick reference guide]
```

### Quick Reference Template

Create a `quick-reference/quick-reference.md` file with:

```markdown
# [Skill Name] Quick Reference

## What It Does
[One-sentence description]

## When to Use
[One-sentence description]

## How to Use
1. [Step 1]
2. [Step 2]
3. [Step 3]

## Key Outputs
- [Output 1]
- [Output 2]

## Tips
- [Tip 1]
- [Tip 2]
```

### Adding Examples

Examples should be:
- **Diverse**: Cover different industries, geographies, and use cases
- **Realistic**: Based on real-world scenarios
- **Complete**: Show full outputs, not partial examples
- **Annotated**: Include explanations of why certain choices were made

## Improving Existing Skills

### Types of Improvements

- **Documentation**: Clarify instructions, add examples, fix typos
- **Templates**: Improve existing templates or add new ones
- **Examples**: Add more diverse examples
- **Framework**: Enhance the methodology with best practices
- **Bug Fixes**: Fix errors or inconsistencies

### Making Changes

1. Fork the repository
2. Create a new branch (`git checkout -b improve-customer-discovery`)
3. Make your changes
4. Test the skill to ensure it works as expected
5. Commit your changes
6. Submit a pull request

## Submission Guidelines

### Pull Request Process

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/claude-innovation-skills.git
   cd claude-innovation-skills
   ```

3. **Create a new branch**:
   ```bash
   git checkout -b feature/your-skill-name
   ```
   or
   ```bash
   git checkout -b fix/issue-description
   ```

4. **Make your changes**:
   - Add new skill folder with proper structure
   - Include all required files (SKILL.md, templates, references)
   - Test your skill with Claude to ensure it works

5. **Commit your changes**:
   ```bash
   git add .
   git commit -m "Add [skill-name] skill for [purpose]"
   ```
   or
   ```bash
   git commit -m "Fix typo in customer-discovery documentation"
   ```

6. **Push to your fork**:
   ```bash
   git push origin feature/your-skill-name
   ```

7. **Submit a Pull Request**:
   - Go to the original repository on GitHub
   - Click "New Pull Request"
   - Select your branch
   - Fill out the PR template with:
     - Description of changes
     - Why the change is needed
     - How you tested it
     - Any relevant screenshots or examples

### Pull Request Template

When submitting a PR, please include:

```markdown
## Description
[Brief description of what this PR does]

## Type of Change
- [ ] New skill
- [ ] Improvement to existing skill
- [ ] Bug fix
- [ ] Documentation update
- [ ] Other (please describe)

## Skill Details (if applicable)
- **Skill Name**:
- **Methodology**:
- **Phase**: Discovery / Definition / Ideation / Evaluation / Validation

## Testing
- [ ] I have tested this skill with Claude
- [ ] The skill works in both interactive and autonomous modes
- [ ] All examples produce expected outputs
- [ ] Documentation is complete and accurate

## Screenshots/Examples
[Include any relevant outputs or screenshots]

## Checklist
- [ ] My code follows the skill structure guidelines
- [ ] I have updated the README.md (if adding a new skill)
- [ ] I have included examples and documentation
- [ ] I have tested my changes thoroughly
- [ ] My changes don't break existing functionality
```

## Quality Standards

### Documentation Quality

- **Clear and Concise**: Use simple language, avoid jargon
- **Complete**: Include all necessary information
- **Accurate**: Ensure all information is correct and up-to-date
- **Well-Formatted**: Use proper markdown formatting

### Code Quality

- **Consistent**: Follow existing patterns and conventions
- **Tested**: Verify that skills work as expected
- **Documented**: Include inline comments where necessary
- **Error-Free**: Check for typos and grammatical errors

### Example Quality

- **Diverse**: Cover different industries and contexts
- **Realistic**: Based on real-world scenarios
- **Complete**: Show full workflows, not partial examples
- **Educational**: Help users understand how to use the skill

## Skill Categories

When adding a new skill, categorize it appropriately:

- **Phase 1: Discovery** - Understanding customers and problems
- **Phase 2: Definition** - Defining solutions and value propositions
- **Phase 3: Ideation** - Generating creative ideas
- **Phase 4: Evaluation** - Evaluating and prioritizing ideas
- **Phase 5: Validation** - Validating assumptions and ideas

## Reporting Issues

Found a bug or have a suggestion? Please:

1. Check if the issue already exists
2. Create a new issue with:
   - Clear title
   - Detailed description
   - Steps to reproduce (if applicable)
   - Expected vs. actual behavior
   - Screenshots or examples (if relevant)

## Code of Conduct

- Be respectful and inclusive
- Provide constructive feedback
- Focus on the work, not the person
- Help others learn and grow
- Credit others for their work

## License

By contributing, you agree that your contributions will be licensed under the same license as the project.

## Questions?

- Open an [issue](https://github.com/thinkbigleaders/claude-innovation-skills/issues) for questions
- Start a [discussion](https://github.com/thinkbigleaders/claude-innovation-skills/discussions) for ideas
- Tag maintainers in your PR if you need feedback

## Recognition

Contributors will be recognized in:
- The README.md contributors section
- Release notes for significant contributions
- The community discussions

Thank you for helping make innovation more accessible to everyone! 🙏

---

**Ready to contribute?** Fork the repository and start adding value!
