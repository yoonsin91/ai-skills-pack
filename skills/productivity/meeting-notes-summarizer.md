# Meeting Notes Summarizer

## 📌 Purpose
Transforms lengthy meeting notes or transcripts into concise summaries with action items and key decisions.

## 🎯 Context
Use after meetings to create structured summaries for distribution to team members and stakeholders.

## 🤖 Prompt/Configuration

```
You are an expert at synthesizing meeting notes into clear, actionable summaries.

Please analyze the following meeting notes and create a structured summary:

[PASTE MEETING NOTES OR TRANSCRIPT]

Meeting context:
- Date: [meeting date]
- Attendees: [list of attendees]
- Purpose: [meeting objective]

Create a summary with:
1. Executive Summary (2-3 sentences)
2. Key Decisions Made
3. Action Items (with owners and due dates if mentioned)
4. Important Discussion Points
5. Next Steps
6. Parking Lot (items tabled for later)

Format: Professional business communication style
```

## 💡 Examples

### Example 1: Project Planning Meeting

**Input:**
```
Team discussed Q1 roadmap. Sarah proposed new feature for user dashboard.
Mike raised concerns about timeline. Agreed to prototype first.
John will research technical requirements. Due next Friday.
Budget approved for $50K. Lisa to send out updated timeline.
```

**Expected Output:**
```
MEETING SUMMARY

Executive Summary:
Team aligned on Q1 roadmap with new user dashboard feature. Prototype-first 
approach adopted to address timeline concerns. Budget of $50K approved.

Key Decisions:
- Proceed with user dashboard feature using prototype approach
- Allocated $50K budget for Q1 initiatives
- Prototype review before full development commitment

Action Items:
1. John - Research technical requirements (Due: Next Friday)
2. Lisa - Send updated project timeline (Due: This week)
3. Sarah - Create initial dashboard prototype (Implied)

Important Discussion Points:
- Timeline concerns raised by Mike addressed through phased approach
- Prototype will validate feasibility before major resource commitment

Next Steps:
- Review John's technical research next Friday
- Schedule prototype review session after initial build
- Reconvene for full roadmap approval
```

## 🔧 Tips & Best Practices

- **Tip 1**: Include meeting context (who, when, why) for better summarization
- **Tip 2**: Specify the desired level of detail (brief/comprehensive)
- **Tip 3**: Indicate target audience (team/executives/stakeholders)

## 📊 Performance Notes

- Works best with: GPT-4, Claude for nuanced understanding
- Limitations: Quality depends on input notes quality
- Alternatives: Combine with transcription tools for recorded meetings

## 🏷️ Tags

`meetings` `productivity` `communication` `collaboration`

## 👤 Author

- Created by: AI Skills Pack Community
- Date: 2025-12-31
- Last updated: 2025-12-31

## 📝 Changelog

- **2025-12-31**: Initial version
