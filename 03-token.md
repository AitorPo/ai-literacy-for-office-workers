# Token

## The Simple Analogy

Tokens are like **puzzle pieces** that AI uses to process text. Just as you might break a complex jigsaw puzzle into manageable pieces, AI breaks your text into chunks called tokens.

Think of it as the AI's "reading units" - not always full words, but meaningful chunks that the AI can understand and process.

## How Words Become Tokens

### Simple Examples

**Short/common words** = 1 token each:
- "the" = 1 token
- "and" = 1 token  
- "cat" = 1 token

**Longer words** might be 1 token:
- "elephant" = 1 token
- "wonderful" = 1 token

**Complex/uncommon words** get broken up:
- "anthropomorphism" = 2 tokens: "anthrop" + "omorphism"
- "telecommunications" = 3 tokens: "tele" + "commun" + "ications"

**Numbers and punctuation**:
- "123" = 1 token
- "1,234,567" = 4 tokens: "1" + "," + "234" + "," + "567"
- "!!!" = 3 tokens: "!" + "!" + "!"

### Real Example Breakdown

**Text**: "Hello! How are you today?"

**Tokens**: 
1. "Hello"
2. "!"
3. "How"
4. "are" 
5. "you"
6. "today"
7. "?"

**Total**: 7 tokens

## Why Tokens Matter for Your Work

### 1. Cost Impact 💰

AI services charge by the token:
- **Input tokens**: What you send (your prompt)
- **Output tokens**: What AI sends back (the response)

**Example Cost Calculation**:
```
Your prompt: 100 tokens
AI response: 300 tokens
Total: 400 tokens charged

If the model costs $0.002 per 1,000 tokens:
Your cost = 400 × $0.002 ÷ 1,000 = $0.0008 (less than a penny)
```

### 2. Length Limits 📏

Every model has a **context window** - maximum tokens it can handle:

| Model | Context Window | Equivalent Pages |
|-------|----------------|------------------|
| GPT-3.5 | 4,000 tokens | ~3 pages |
| GPT-4 | 8,000-32,000 tokens | ~6-25 pages |
| Claude 3 | 200,000 tokens | ~150 pages |

**What happens when you exceed the limit?**
- AI "forgets" earlier parts of long conversations
- Large documents get truncated
- Complex tasks fail to complete

### 3. Performance Impact ⚡

More tokens = slower response time and higher cost
- Keep prompts concise but clear
- Break large tasks into smaller chunks
- Use appropriate models for document size

## Practical Office Strategies

### Writing Efficient Prompts

**Inefficient** (wastes tokens):
```
"I would really appreciate it if you could please help me write an email to our client regarding the meeting that we had scheduled for next Tuesday, and I need to reschedule it to Thursday instead, and I want to make sure the tone is professional and apologetic."
```
*Token count: ~50*

**Efficient** (saves tokens):
```
"Write a professional, apologetic email rescheduling Tuesday's client meeting to Thursday."
```
*Token count: ~15*

### Managing Long Documents

**Problem**: 50-page report exceeds token limit

**Solutions**:
1. **Chunk it**: Analyze 10 pages at a time
2. **Summarize first**: Get AI to create executive summary, then ask detailed questions
3. **Extract key sections**: Focus on specific chapters/sections
4. **Use high-capacity models**: Claude 3 for very long documents

### Token Estimation Tips

**Quick estimation**:
- **1 token ≈ 4 characters** (including spaces)
- **1 token ≈ 0.75 words** on average
- **100 words ≈ 130-150 tokens**

**Tools to check exact count**:
- OpenAI's tokenizer tool
- Character/word count ÷ 4 (rough estimate)

## Common Token-Related Issues

### "Conversation Too Long" Error
**Problem**: Multi-turn conversation exceeds context window
**Solution**: Start fresh conversation or summarize previous discussion

### "Incomplete Response" 
**Problem**: AI stops mid-sentence
**Solution**: Ask AI to continue, or break request into smaller parts

### High Unexpected Costs
**Problem**: Bills are higher than expected
**Solution**: Monitor token usage, use simpler models for simple tasks

## Money-Saving Token Tips

1. **Be concise**: Remove unnecessary words from prompts
2. **Use examples sparingly**: Each example adds tokens
3. **Choose right model**: Don't use GPT-4 for simple tasks
4. **Reuse context**: Build on previous responses instead of repeating context
5. **Batch similar requests**: Handle multiple similar tasks in one prompt

## Key Takeaway

Tokens are the **currency** of AI interaction:
- They determine your costs
- They limit how much you can process at once
- They affect response speed

Think of tokens like **text data usage** - be mindful but don't obsess over every single token.

---

**Next**: Master the art of [Prompting](./04-prompt.md) to get better AI responses.