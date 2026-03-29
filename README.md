┌──────────────────────────────────────────────────────────────────────────────┐
│                                                                              │
│                      MVP IDEA GENERATOR SKILL PACK                           │
│                                                                              │
│          Dig Reddit for real pain points, generate 7-day MVP solutions       │
│                                                                              │
└──────────────────────────────────────────────────────────────────────────────┘

# MVP Idea Generator Skill Pack

[中文文档](README_zh.md) | English

A skill pack that digs into Reddit to find real pain points and generates actionable MVP solutions. Helps indie developers, SaaS founders, cross-border entrepreneurs, and AI tool developers quickly validate product ideas and design minimum viable products.

## Features

- **Vertical Community Discovery** - Automatically finds high-value, high-activity Reddit Subreddits
- **Pain Point Sniffing** - Extracts real, high-frequency user needs from community discussions
- **MVP Generation** - Designs single-core-feature, 7-day-buildable minimum viable product solutions
- **Validation Copy** - Generates Reddit-compliant validation post templates
- **Business Scoring** - Objectively evaluates project feasibility (5-dimension scoring system)

## Installation

### Clone from GitHub
```bash
git clone https://github.com/ange-web3/mvp-skills.git
cd mvp-skills
```

### Install to OpenCode
Copy the skill pack to OpenCode's skills directory:
```bash
cp -r skills/* ~/.config/opencode/skills/
```

Or use symlinks (recommended for development):
```bash
ln -s $(pwd)/skills/* ~/.config/opencode/skills/
```

### Verify Installation
Restart OpenCode and check if the skill is available:
```
Please list all available skills
```
You should see the `mvp-idea-generator` skill.

## Usage Examples

### Basic Usage
The skill automatically triggers when users mention product idea validation, market pain point analysis, or MVP design.

**Example 1: AI Writing Tool Idea Validation**
```
User input: "I want to build an AI tool but don't know what direction"
Skill execution:
1. Locates writing-related Subreddits
2. Discovers high-frequency pain point: "Novelists need character consistency checking tool"
3. Designs "Character Consistency Checker" MVP
4. Generates validation post draft
5. Outputs business feasibility score (38/50, recommended to try)
```

**Example 2: Cross-border E-commerce Tool Idea**
```
User input: "What pain points do cross-border e-commerce sellers have?"
Skill execution:
1. Locates e-commerce Subreddits
2. Discovers pain point: "Multi-platform inventory synchronization is difficult"
3. Designs "Simple Inventory Sync" MVP
4. Generates problem validation post
5. Outputs score (32/50, recommends market segmentation)
```

## Skill Pack Contents

### Main Skill
- **mvp-idea-generator** - MVP idea generator with complete five-stage workflow

### Reference Documents
- [Community Discovery Guide](skills/mvp-idea-generator/references/subreddit-discovery-guide.md)
- [Pain Point Analysis Framework](skills/mvp-idea-generator/references/pain-point-analysis-framework.md)
- [MVP Design Principles](skills/mvp-idea-generator/references/mvp-design-principles.md)
- [Business Scoring Rubric](skills/mvp-idea-generator/references/commercial-scoring-rubric.md)

### Output Assets
- [Validation Post Templates](skills/mvp-idea-generator/assets/validation-post-templates.md)

## Workflow

1. **Vertical Community Discovery** - Find high-quality target Subreddits
2. **Pain Point Sniffing** - Extract real needs from community discussions
3. **MVP Generation** - Design 7-day-buildable minimum viable products
4. **Validation Copy** - Generate Reddit-compliant validation posts
5. **Business Scoring** - Evaluate project feasibility (50-point scale)

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Create a Pull Request

### Developing New Skills
1. Create a new skill folder under the `skills/` directory
2. Follow the skill pack structure:
   ```
   your-skill/
   ├── SKILL.md          # Skill description and instructions
   ├── references/       # Reference documents (optional)
   └── assets/           # Output assets (optional)
   ```
3. Update the skill list in this README

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- Email: qson8888@gmail.com

## Acknowledgments

- Thanks to all indie developers who provided feedback and suggestions
- Thanks to the Reddit community for providing real user pain point data