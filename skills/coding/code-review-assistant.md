# Code Review Assistant

## 📌 Purpose
Provides comprehensive code reviews focusing on best practices, potential bugs, performance, and maintainability.

## 🎯 Context
Use this skill when you need a thorough review of your code changes before committing or during pull request reviews.

## 🤖 Prompt/Configuration

```
You are an expert code reviewer with deep knowledge of software engineering best practices.

Please review the following code and provide feedback on:
- Code quality and readability
- Potential bugs or edge cases
- Performance considerations
- Security vulnerabilities
- Best practices and design patterns
- Test coverage suggestions

Code to review:
[PASTE YOUR CODE HERE]

Format your response as:
1. Overall Assessment (Good/Needs Improvement/Critical Issues)
2. Specific Issues (categorized by severity: Critical, High, Medium, Low)
3. Suggestions for improvement
4. Positive aspects worth noting
```

## 💡 Examples

### Example 1: JavaScript Function Review

**Input:**
```javascript
function processUser(user) {
  return user.name.toUpperCase();
}
```

**Expected Output:**
```
Overall Assessment: Needs Improvement

Critical Issues:
- No null/undefined check for user parameter
- No validation for user.name existence

Suggestions:
- Add input validation
- Handle edge cases
- Consider adding TypeScript for type safety

Improved version:
function processUser(user) {
  if (!user || typeof user.name !== 'string') {
    throw new Error('Invalid user object');
  }
  return user.name.toUpperCase();
}
```

## 🔧 Tips & Best Practices

- **Tip 1**: Provide complete context including language, framework, and project requirements
- **Tip 2**: Include related code or dependencies for better analysis
- **Tip 3**: Ask for specific areas of concern if you have particular worries

## 📊 Performance Notes

- Works best with: GPT-4, Claude, or similar advanced models
- Limitations: May miss domain-specific issues without proper context
- Alternatives: Use with static analysis tools for comprehensive coverage

## 🏷️ Tags

`code-review` `quality` `best-practices` `coding`

## 👤 Author

- Created by: AI Skills Pack Community
- Date: 2025-12-31
- Last updated: 2025-12-31

## 📝 Changelog

- **2025-12-31**: Initial version
