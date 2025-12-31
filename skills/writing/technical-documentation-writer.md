# Technical Documentation Writer

## 📌 Purpose
Transforms technical concepts and code into clear, comprehensive documentation suitable for different audiences.

## 🎯 Context
Use when creating README files, API documentation, user guides, or technical specifications.

## 🤖 Prompt/Configuration

```
You are a technical documentation specialist who excels at making complex topics accessible.

Please create documentation for the following:
[DESCRIBE YOUR PROJECT/FEATURE/API]

Target audience: [developers/end-users/technical writers]

Include:
- Clear overview and purpose
- Installation/setup instructions
- Usage examples with code snippets
- Configuration options
- Common issues and troubleshooting
- Best practices

Style guidelines:
- Use clear, concise language
- Include practical examples
- Add visual aids where helpful (diagrams, tables)
- Follow markdown best practices
```

## 💡 Examples

### Example 1: API Endpoint Documentation

**Input:**
```
Function: getUserProfile(userId)
Returns user profile data including name, email, preferences
```

**Expected Output:**
```markdown
## Get User Profile

Retrieves detailed profile information for a specific user.

### Endpoint
GET /api/users/{userId}/profile

### Parameters
| Name | Type | Required | Description |
|------|------|----------|-------------|
| userId | string | Yes | Unique user identifier |

### Response
{
  "name": "John Doe",
  "email": "john@example.com",
  "preferences": {...}
}

### Example
curl -X GET https://api.example.com/users/123/profile

### Error Codes
- 404: User not found
- 401: Unauthorized
```

## 🔧 Tips & Best Practices

- **Tip 1**: Specify the exact documentation format you need (README, API docs, tutorial)
- **Tip 2**: Provide code samples or technical specifications for accuracy
- **Tip 3**: Indicate the target audience's technical level

## 📊 Performance Notes

- Works best with: GPT-4, Claude for technical accuracy
- Limitations: May need fact-checking for highly specialized domains
- Alternatives: Combine with existing documentation tools

## 🏷️ Tags

`documentation` `technical-writing` `api-docs` `writing`

## 👤 Author

- Created by: AI Skills Pack Community
- Date: 2025-12-31
- Last updated: 2025-12-31

## 📝 Changelog

- **2025-12-31**: Initial version
