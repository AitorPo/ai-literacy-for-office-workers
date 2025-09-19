# AI Quick Reference Cheat Sheet

*Print this page for easy reference at your desk*

## 🧠 Core AI Concepts

| Concept | One-Sentence Description | When to Use |
|---------|-------------------------|-------------|
| **LLM** | Autocomplete engine that learned language patterns from the internet | Understanding AI capabilities/limits |
| **Model** | Specific AI "engine" optimized for different tasks | Choosing the right tool |
| **Token** | Text chunks AI processes (affects cost & limits) | Managing costs & length |
| **Prompt** | Your instruction manual for AI | Getting better results |
| **Temperature** | Creativity dial (low=predictable, high=creative) | Matching task to output style |
| **Agent** | AI that can take actions, not just give advice | Automating multi-step tasks |
| **Hallucination** | When AI confidently states false information | Fact-checking AI output |
| **Fine-tuning** | Training AI on your company's specific data | Creating specialized AI |

---

## 🎯 Temperature Quick Guide

| Task Type | Temperature | Example |
|-----------|-------------|---------|
| **Data/Facts** | 0.1-0.3 ❄️ | Extracting numbers, calculations |
| **Business Writing** | 0.4-0.6 🌡️ | Emails, reports, procedures |
| **Creative Tasks** | 0.7-1.0 🔥 | Brainstorming, marketing ideas |

---

## ✍️ Prompt Formula

**The CLEAR Framework:**
```
Context: What's the situation?
Length: How long should response be?
Examples: Show what good looks like
Audience: Who is this for?
Role: What role should AI play?
```

**Quick Template:**
```
Role: You are a [job title]
Task: [What you want done]
Context: [Relevant background]
Audience: [Who will see this]
Format: [How to structure output]
Tone: [Professional/casual/etc.]
```

---

## 🚨 Hallucination Warning Signs

**Always verify** when AI provides:
- ❌ Specific statistics or percentages
- ❌ Citations, studies, or sources
- ❌ Current events or recent data
- ❌ Company-specific information
- ❌ Technical configuration steps
- ❌ Legal or compliance advice

**Red flags:**
- Overly specific details (exactly 1,247 participants)
- Perfect round numbers (exactly 25% increase)
- Too-convenient sources
- Confident certainty about uncertain topics

---

## 💰 Token Cost Management

**Quick Estimation:**
- 1 token ≈ 4 characters
- 1 token ≈ 0.75 words
- 100 words ≈ 130-150 tokens

**Money-saving tips:**
- ✅ Use simpler models for simple tasks
- ✅ Be concise but clear in prompts
- ✅ Don't regenerate unnecessarily
- ✅ Choose right model for the job

---

## 🔧 Model Selection Guide

**Quick Decision Tree:**
- **Need it fast & cheap?** → GPT-3.5, Claude Instant
- **Quality is critical?** → GPT-4, Claude 3 Opus
- **Long documents?** → Claude 3 (large context)
- **Current web info?** → Bing Chat, Bard
- **Coding tasks?** → GitHub Copilot, GPT-4

---

## ✅ Safe AI Practices

### **Green Light** (Generally Safe) 🟢
- Brainstorming and ideation
- Writing assistance and editing
- Creating templates and frameworks
- Explaining concepts
- Draft creation

### **Yellow Light** (Verify Key Facts) 🟡
- Business reports and presentations
- Process documentation
- Customer communications
- Data analysis summaries

### **Red Light** (High Risk - Verify Everything) 🔴
- Financial decisions and calculations
- Legal compliance information
- Technical implementation steps
- Medical or safety advice
- Current events and recent data

---

## 🎭 Role-Based AI Usage

### **Accountants/Finance**
- Default: Low temperature
- Best for: Data extraction, calculations, financial modeling
- Verify: All numbers, formulas, compliance info

### **Marketing/Creative**
- Default: High temperature
- Best for: Content creation, brainstorming, campaign ideas
- Verify: Statistics, competitor claims, market data

### **Operations/Process**
- Default: Low temperature
- Best for: Documentation, procedures, workflow optimization
- Verify: Technical steps, compliance requirements

### **Sales**
- Default: Medium temperature
- Best for: Email templates, proposal writing, objection handling
- Verify: Product specs, pricing, competitor info

### **HR**
- Default: Medium temperature
- Best for: Policy explanations, communication templates
- Verify: Legal requirements, company policies

---

## 🆘 Emergency Troubleshooting

**"AI gave me wrong information"**
→ Check if it was hallucination-prone content → Verify with original sources

**"Response is too generic"**
→ Add more context to prompt → Specify role and audience

**"AI won't follow my instructions"**
→ Break complex requests into steps → Use examples in prompt

**"Response is too long/short"**
→ Specify exact length requirements → Use bullet points for structure

**"Conversation got too long and AI forgot earlier context"**
→ Start new conversation → Summarize key points in new prompt

---

## 📞 Getting Help

1. **Check this cheat sheet first**
2. **Search company knowledge base**
3. **Ask IT team for technical issues**
4. **Consult with colleagues who use AI regularly**
5. **Review full concept guides for deeper understanding**

---

*Keep this reference handy - master these concepts and you'll be an AI power user!*