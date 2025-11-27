# Downloadable Skill Files

This folder contains ready-to-use `.skill` files that you can download and upload directly to Claude.

## What are .skill files?

`.skill` files are packaged skill folders that contain all the templates, references, and instructions Claude needs to help you with innovation activities. They're essentially zip files with a `.skill` extension for easy identification.

## How to Download

1. Click on any `.skill` file in this folder
2. Click the "Download" button (or right-click and select "Save As...")
3. Save the file to your computer

## How to Upload to Claude

### Method 1: Via Claude.ai Web Interface

1. Go to [Claude.ai](https://claude.ai)
2. Start a new conversation or open an existing project
3. Look for the skill/tool icon in the interface
4. Click "Upload Skill" or "Add Custom Skill"
5. Select the `.skill` file you downloaded
6. The skill is now available! Use it by typing `/` and selecting the skill name

### Method 2: Via Claude Desktop App

1. Open Claude Desktop
2. Go to Settings → Skills
3. Click "Add Skill"
4. Select the `.skill` file you downloaded
5. The skill is now available in all your conversations

### Method 3: Manual Installation (Advanced)

1. Rename the `.skill` file to `.zip` (e.g., `customer-discovery.skill` → `customer-discovery.zip`)
2. Extract the zip file
3. Copy the extracted folder to your Claude skills directory:
   - **macOS/Linux**: `~/.claude/skills/`
   - **Windows**: `%USERPROFILE%\.claude\skills\`
4. The skill is now installed!

## Available Skills

### Phase 1: Discovery
- **customer-discovery.skill** - Understand customer needs through JTBD and persona creation

### Phase 2: Definition
- **solution-definition.skill** - Define solutions using Working Backwards (PRFAQ)
- **prfaq-writer.skill** - Amazon-style Press Release FAQ writer

### Phase 3: Ideation
- **ideation-scamper.skill** - Complete SCAMPER framework (all 7 techniques)
- **scamper-substitute.skill** - Substitute components
- **scamper-combine.skill** - Combine elements
- **scamper-adapt.skill** - Adapt to new contexts
- **scamper-modify.skill** - Modify and magnify
- **scamper-put-to-other-uses.skill** - New uses for existing solutions
- **scamper-eliminate.skill** - Simplify by removing
- **scamper-reverse.skill** - Reverse or rearrange

### Phase 4: Evaluation
- **idea-evaluation.skill** - Multi-criteria scoring framework

### Phase 5: Validation
- **critical-validation.skill** - Six Thinking Hats methodology

## Usage Tips

1. **Start with customer-discovery** - Build a strong foundation by understanding your customers first
2. **Use interactive mode** - If you're new to a skill, use interactive mode for step-by-step guidance
3. **Combine skills** - Use multiple skills in sequence for a complete innovation workflow
4. **Save outputs** - Keep the outputs from each skill to build a comprehensive innovation document

## Need Help?

- Check the main [README](../README.md) for detailed documentation
- Visit the [GitHub repository](https://github.com/thinkbigleaders/claude-innovation-skills) for examples
- Open an [issue](https://github.com/thinkbigleaders/claude-innovation-skills/issues) if you encounter problems

---

**Happy innovating!** 🚀
