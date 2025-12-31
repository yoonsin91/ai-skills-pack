# Data Analysis Interpreter

## 📌 Purpose
Analyzes datasets and provides insights, patterns, and actionable recommendations in plain language.

## 🎯 Context
Use when you need to understand data trends, identify patterns, or make data-driven decisions without deep statistical expertise.

## 🤖 Prompt/Configuration

```
You are a data analyst who excels at extracting insights from data and explaining them clearly.

Analyze the following data:
[PASTE DATA OR DESCRIBE DATASET]

Please provide:
1. Key findings and patterns
2. Statistical summary (if applicable)
3. Trends and anomalies
4. Actionable insights
5. Recommendations based on the data
6. Visualizations suggestions (charts, graphs)

Context about the data:
- Source: [where the data comes from]
- Time period: [relevant dates]
- Goal: [what you want to learn]

Format response for: [technical/non-technical] audience
```

## 💡 Examples

### Example 1: Sales Data Analysis

**Input:**
```
Monthly Sales Data (Last 6 months):
Jan: $50,000
Feb: $48,000
Mar: $55,000
Apr: $62,000
May: $58,000
Jun: $70,000

Analyze trends and provide recommendations.
```

**Expected Output:**
```
Key Findings:
- 40% growth from January to June ($50K → $70K)
- Steady upward trend with minor dip in February
- Accelerated growth in Q2 (Apr-Jun)

Insights:
- Strong overall performance with 6.7% average monthly growth
- February dip may indicate seasonal factors or market conditions
- Q2 acceleration suggests successful initiatives or market expansion

Recommendations:
1. Investigate February causes to prevent future dips
2. Replicate Q2 success factors in upcoming quarters
3. Set Q3 target at $75K-80K based on current trajectory
4. Monitor for sustainability of growth rate

Visualization: Line chart showing monthly progression with trend line
```

## 🔧 Tips & Best Practices

- **Tip 1**: Provide context about what the data represents and business goals
- **Tip 2**: Specify if you need statistical analysis or high-level insights
- **Tip 3**: Mention any specific metrics or KPIs you're tracking

## 📊 Performance Notes

- Works best with: GPT-4, Claude for complex analysis
- Limitations: Cannot process actual files directly; requires pasted data or descriptions
- Alternatives: Combine with data visualization tools for comprehensive analysis

## 🏷️ Tags

`data-analysis` `insights` `statistics` `analysis`

## 👤 Author

- Created by: AI Skills Pack Community
- Date: 2025-12-31
- Last updated: 2025-12-31

## 📝 Changelog

- **2025-12-31**: Initial version
