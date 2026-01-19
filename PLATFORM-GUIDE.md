# Platform-Specific Guide: Nonfiction Study Partner

## How Different AIs Handle This Prompt

### ChatGPT (GPT-4/4o)
**Strengths:**
- Great at following structured templates
- Can save as a Custom GPT for repeated use
- Good at maintaining consistency across long outputs

**Tips for Best Results:**
- Use the full prompt as-is
- If output gets cut off, say "continue" and it will pick up where it left off
- Consider creating a Custom GPT with this prompt for easy reuse
- Works best with ChatGPT Plus, Team, or Enterprise

**Potential Issues:**
- May occasionally skip sections if the book is very long
- Sometimes adds unnecessary emojis (just ask it to remove them)

---

### Claude (Sonnet/Opus)
**Strengths:**
- Excellent at nuanced analysis and connecting ideas
- Great at longer-form, detailed breakdowns
- Superior at maintaining context across complex requests
- Better at understanding "why it matters" insights

**Tips for Best Results:**
- The prompt works perfectly as-is
- Claude handles the full complexity in one shot
- Ask for clarification or deeper dives - Claude excels at this
- Best for books with complex ideas or interdisciplinary connections

**Potential Issues:**
- None significant - this prompt is well-suited to Claude's strengths

---

### Google Gemini
**Strengths:**
- Fast responses
- Good at structured summaries
- Handles multiple formats well

**Tips for Best Results:**
- Use the full prompt
- May need to be more explicit about formatting (e.g., "use markdown headers")
- Works well for business books and practical nonfiction
- Free tier works fine for this

**Potential Issues:**
- Sometimes produces shorter outputs than requested
- May need to ask for more detail on specific sections
- Can be less insightful on the "why it matters" sections

---

### Microsoft Copilot
**Strengths:**
- Quick summaries
- Integrated with Microsoft tools
- Good for basic breakdowns

**Tips for Best Results:**
- Break the prompt into smaller chunks
- Start with Quick Start + Chapter breakdown only
- Then request Insight Layer separately
- Then request Application Pack separately
- Best for straightforward business/professional books

**Potential Issues:**
- Struggles with the full complexity in one request
- May produce more generic insights
- Less detailed than other platforms
- Better for simpler books or when you need quick summaries

---

## Recommended Platform by Book Type

| Book Type | Best Platform | Why |
|-----------|---------------|-----|
| Dense academic/theoretical | Claude | Best at connecting complex ideas |
| Business/leadership | ChatGPT or Claude | Either works great |
| Self-help/practical | Any platform | All handle well |
| Technical/specialized | Claude or ChatGPT | Better domain understanding |
| Biographies | ChatGPT or Claude | Better narrative analysis |

---

## How to Modify for Shorter Outputs

If you want a faster, lighter version, use this simplified prompt:

**Quick Version:**
```
You are my Nonfiction Study Partner. For the book I provide, create:

1. Quick Start: thesis, 10 key ideas, 3 action items
2. Chapter summaries: purpose, key points, one application exercise each
3. 7-day practice plan
4. One-page cheat sheet
5. 3 next book recommendations

Book: [Title] by [Author]
My purpose: [Why I'm reading it]
My context: [Your role/situation]
```

This works on all platforms and takes about 1/3 the time.

---

## Troubleshooting

**"The output stopped mid-sentence"**
- ChatGPT/Gemini: Type "continue"
- Claude: Type "please continue" or "keep going"
- Copilot: May need to re-request the specific section

**"Too generic/not enough detail"**
- Add more context about your role and purpose upfront
- Ask follow-up questions on specific sections
- Claude: Ask for "deeper analysis" or "more nuanced connections"
- ChatGPT: Ask to "expand on [specific section]"

**"Wrong format"**
- Be explicit: "Use markdown headers" or "No emojis"
- Paste a sample format if needed

**"Skipped a section"**
- Just ask: "Can you add the [missing section]?"
- All platforms handle this well

---

## Advanced Use: Custom GPTs (ChatGPT Only)

If you have ChatGPT Plus/Team/Enterprise:

1. Go to "Explore GPTs" → "Create a GPT"
2. Name it "Nonfiction Study Partner"
3. Paste the full prompt into Instructions
4. Add this to the description: "Turn any nonfiction book into a complete learning system"
5. Save it

Now you can just select your custom GPT and provide the book info - no need to paste the prompt each time.
