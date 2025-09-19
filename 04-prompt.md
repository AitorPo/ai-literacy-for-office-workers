# Prompt

## The Simple Analogy

A prompt is like **giving directions to a new employee**. The quality of your instructions directly determines the quality of the work you get back.

Think of it as the **only way you can communicate** with AI about what you want - so make it count!

## What Makes a Good Prompt

### The CLEAR Framework

**C - Context**: What's the situation?
**L - Length**: How long should the response be?
**E - Examples**: Show what good looks like
**A - Audience**: Who is this for?
**R - Role**: What role should AI play?

## Prompt Anatomy: Before and After

### ❌ Bad Prompt
```
"Write an email about the meeting."
```

**Problems**: Vague, no context, unclear audience, no specifics

### ✅ Good Prompt
```
**Role**: You are a professional project manager.

**Context**: Our Q3 planning meeting scheduled for Tuesday 2PM has been postponed due to budget approval delays.

**Task**: Write an email to the 8-person project team explaining the postponement.

**Audience**: Internal team members (mix of technical and business roles)

**Tone**: Professional but reassuring

**Length**: Keep it under 150 words

**Include**: 
- Reason for postponement
- New date (TBD this week)
- What team should do in meantime
- Apology for short notice
```

## The Prompt Hierarchy: From Basic to Advanced

### Level 1: Basic Request
```
"Summarize this article."
```

### Level 2: Specific Request
```
"Summarize this article in 3 bullet points focusing on the main business implications."
```

### Level 3: Detailed Context
```
Role: You are a business analyst
Task: Summarize this article about AI in manufacturing
Audience: C-level executives who need quick insights
Format: 3 bullet points
Focus: Business implications and potential ROI
Tone: Professional and data-driven
```

### Level 4: Advanced with Examples
```
Role: You are a business analyst
Task: Summarize this article about AI in manufacturing
Audience: C-level executives who need quick insights

Format: Follow this structure:
• Business Impact: [key business implications]
• Financial Implications: [costs, savings, ROI potential] 
• Strategic Recommendations: [what we should consider]

Tone: Professional and data-driven
Length: Each bullet point should be 1-2 sentences max

Example of good output:
• Business Impact: AI implementation could reduce production costs by 15-20% while improving quality control accuracy.
```

## Prompt Templates for Common Office Tasks

### Email Writing
```
Role: Professional [your job title]
Task: Write a [type] email
To: [recipient and relationship]
About: [main topic/purpose]
Tone: [professional/friendly/urgent/apologetic]
Key points to include:
- [point 1]
- [point 2]
- [point 3]
Length: [word/paragraph limit]
```

### Document Analysis
```
Role: [relevant expert role]
Task: Analyze this [document type]
Focus: [specific aspects to analyze]
Output format: [bullets/paragraphs/table]
Audience: [who will read your analysis]
Key questions to answer:
1. [question 1]
2. [question 2]
3. [question 3]
```

### Meeting Preparation
```
Role: Meeting facilitator
Task: Create an agenda for [meeting type]
Attendees: [list or description]
Duration: [time limit]
Main objective: [primary goal]
Key topics to cover:
- [topic 1 with time allocation]
- [topic 2 with time allocation]
Format: Include time slots and expected outcomes
```

## Advanced Prompting Techniques

### Chain of Thought
Ask AI to show its reasoning:
```
"Before giving your final answer, walk me through your thinking process step by step."
```

### Role-Playing
Make AI adopt a specific perspective:
```
"You are a skeptical CFO reviewing this proposal. What concerns would you raise?"
```

### Constraint Setting
Define clear boundaries:
```
"Limit your response to exactly 3 recommendations, each with a specific action and timeline."
```

### Multi-Step Prompting
Break complex tasks into steps:
```
"First, identify the main problems in this document. Then, for each problem, suggest 2 solutions. Finally, rank all solutions by feasibility."
```

## Common Prompting Mistakes

### 1. Being Too Vague ❌
```
"Help me with this presentation."
```
**Fix**: Specify what kind of help you need

### 2. No Context ❌
```
"Write a proposal."
```
**Fix**: Explain the situation, audience, and purpose

### 3. Assuming AI Knows Your Business ❌
```
"How should we handle the Johnson situation?"
```
**Fix**: Provide background information

### 4. No Quality Criteria ❌
```
"Make this better."
```
**Fix**: Define what "better" means specifically

### 5. Overloading Single Prompt ❌
```
"Analyze this report, write a summary, create action items, draft an email to stakeholders, and suggest a presentation outline."
```
**Fix**: Break into separate, focused prompts

## Iterative Prompting Strategy

### Round 1: Get the Foundation
```
"Write a draft proposal for implementing AI chatbot customer service."
```

### Round 2: Refine and Specify
```
"Revise this proposal to focus more on cost savings and include specific metrics for success."
```

### Round 3: Polish and Perfect
```
"Make the tone more executive-friendly and add a risk mitigation section."
```

## Testing and Improving Your Prompts

### A/B Test Your Prompts
Try different versions and compare results:

**Version A**: "Explain this concept simply."
**Version B**: "Explain this concept as if you're teaching it to a smart colleague who's new to the field."

### Keep a Prompt Library
Save your best prompts for reuse:
- Email templates
- Analysis frameworks  
- Meeting agenda formats
- Report structures

## Key Takeaway

**Great prompts = Great results**

Think of prompting like **briefing a consultant**:
- Give them context
- Be specific about what you want
- Define success criteria
- Provide examples when helpful

The 30 seconds you spend crafting a good prompt will save you 10 minutes of back-and-forth refinement.

---

**Next**: Learn about [Temperature](./05-temperature.md) and how to control AI creativity.