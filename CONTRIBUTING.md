# Contributing to AI Skills Pack

Thank you for your interest in sharing your AI skills! This guide will help you contribute effectively.

## 🎯 What to Contribute

We welcome:
- **AI Prompts**: Effective prompts you use regularly at work
- **Workflow Configurations**: AI tool setups and configurations
- **Skill Templates**: Reusable patterns for common tasks
- **Tips & Tricks**: Best practices and optimization techniques

## 📝 How to Contribute

### 1. Choose the Right Category

Place your skill in the appropriate directory:
- `skills/coding/` - Code generation, review, debugging, refactoring
- `skills/writing/` - Documentation, content creation, communication
- `skills/analysis/` - Data analysis, research, insights
- `skills/productivity/` - Automation, organization, efficiency

Not sure? Create a new category or ask in an issue!

### 2. Use the Template

Copy `/templates/skill-template.md` and fill it out completely:

```bash
cp templates/skill-template.md skills/[category]/[your-skill-name].md
```

### 3. Follow Naming Conventions

- Use lowercase with hyphens: `code-review-assistant.md`
- Be descriptive: `api-documentation-generator.md` not `api-doc.md`
- Avoid version numbers in filename

### 4. Write Quality Content

A good skill submission includes:

✅ **Clear Purpose**: What problem does it solve?
✅ **Complete Prompt**: The full AI prompt or configuration
✅ **Real Examples**: Actual input/output demonstrations
✅ **Practical Tips**: Lessons learned from using it
✅ **Proper Tags**: Help others discover your skill

### 5. Submit Your Contribution

1. Fork this repository
2. Create a new branch: `git checkout -b add-my-skill`
3. Add your skill file
4. Commit: `git commit -m "Add [skill name]"`
5. Push: `git push origin add-my-skill`
6. Open a Pull Request

## ✨ Quality Guidelines

### Do's ✅
- ✅ Test your prompt before sharing
- ✅ Include concrete examples
- ✅ Explain when to use (and when NOT to use) the skill
- ✅ Credit original sources if adapting existing prompts
- ✅ Update the main README.md if adding a new category

### Don'ts ❌
- ❌ Share proprietary or confidential prompts
- ❌ Include company-specific information
- ❌ Copy commercial prompts without permission
- ❌ Submit untested or hypothetical skills

## 🔍 Review Process

1. **Automated Checks**: Basic formatting and structure validation
2. **Community Review**: Other contributors may provide feedback
3. **Maintainer Approval**: Final review by maintainers
4. **Merge**: Your skill is added to the repository!

## 💡 Tips for Great Contributions

### Make It Reusable
```markdown
❌ Bad: "Review the login code in our app"
✅ Good: "Review [PASTE CODE] for security and best practices"
```

### Provide Context
```markdown
❌ Bad: "Write documentation"
✅ Good: "Create API documentation for [FEATURE] targeting [AUDIENCE]"
```

### Include Real Examples
Show actual before/after or input/output from using your skill.

### Tag Appropriately
Use relevant tags to help others discover your skill:
- Technical level: `beginner`, `intermediate`, `advanced`
- Domain: `backend`, `frontend`, `devops`, `data-science`
- Task type: `debugging`, `optimization`, `learning`

## 🆘 Need Help?

- **Questions**: Open an issue with the `question` label
- **Ideas**: Open an issue with the `idea` label
- **Problems**: Open an issue with the `bug` label

## 📜 Code of Conduct

- Be respectful and inclusive
- Provide constructive feedback
- Share knowledge generously
- Give credit where due

## 🎉 Recognition

Contributors will be:
- Listed in the skill's author section
- Mentioned in release notes
- Recognized in the community

Thank you for making AI more accessible and effective for everyone! 🚀
