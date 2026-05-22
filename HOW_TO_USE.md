# How to Use the Career Guidance Skill

## Installation

### For Claude.ai Users

1. **Download the skill**
   - Go to the GitHub repository and download `career-guidance.skill`

2. **Upload to Claude.ai**
   - Go to [claude.ai](https://claude.ai)
   - Start a new conversation
   - Look for the **paperclip/attachment icon** or **file upload** option
   - Select and upload the `career-guidance.skill` file
   - Claude will automatically recognize and load the skill

3. **Verify it's loaded**
   - At the top of the conversation, you should see a note indicating the skill is active
   - Or simply ask: "Do you have the career guidance skill loaded?" and Claude will confirm

### For Claude Desktop App Users

1. **Locate your skills directory**
   - Mac: `~/.claude/skills/`
   - Windows: `%APPDATA%\Claude\skills\`
   - Linux: `~/.config/claude/skills/`

2. **Copy the skill file**
   - Copy `career-guidance.skill` into your skills directory
   - Or copy the entire `career-guidance-skill/` folder

3. **Restart Claude Desktop**
   - Close and reopen the Claude Desktop app
   - The skill will be automatically loaded

4. **Verify it's loaded**
   - Open a conversation
   - You should see the skill listed in your available skills
   - Or ask Claude: "What skills do you have loaded?"

### For Claude API Users

Skills are built into the Claude chat interfaces (Claude.ai and Claude Desktop). **The skill format is not compatible with the Claude API** — the API does not support `.skill` files.

If you're using the API, you have two options:

**Option 1: Copy the SKILL.md content into your system prompt**
- Extract the content from `SKILL.md` 
- Paste it directly into your system prompt when making API calls
- The instructions will work the same way

**Option 2: Use the web interface**
- Use Claude.ai instead, which supports skills natively
- Upload the skill there instead of building it into your API integration

---

## How to Use It

Once the skill is loaded, you don't need to do anything special. Just start a conversation about your career.

### Example prompts that will trigger the skill:

- "I need help with my career"
- "I want to switch careers"
- "I feel stuck at work and don't know what to do"
- "What career should I choose?"
- "How do I break into product management?"
- "Should I quit my job?"
- "I'm thinking about starting my own business but I'm scared"
- "Can you help me with my resume?"
- "I just got laid off and I'm lost"
- "I'm mid-career and burnt out"
- "How do I get a raise?"
- "Help me with interview prep"

### What to expect

The skill will:

1. **Listen and ask questions** — It won't dump a 5-year plan on you immediately. It'll ask targeted questions to understand your situation, motivations, and constraints.

2. **Be honest** — If your expectations are unrealistic (like becoming an ML engineer in 3 months), it will tell you directly — and give you a real timeline instead.

3. **Get specific** — You won't get generic advice. All recommendations will be tailored to *your* strengths, motivations, and situation.

4. **Structure the guidance** — You'll get tables, sequenced skill plans, concrete monthly roadmaps, and specific resources — not just prose.

5. **Challenge your thinking** — It will ask uncomfortable questions like "Are you running from something or running toward something?" or "Are you sure this is about the career, not the company?"

---

## What It Can Help With

✅ **Direction Finding**
- Figuring out what career is actually right for you
- Exploring 3–5 realistic options instead of one dream job
- Understanding the market realities of different paths

✅ **Skill Gap Analysis**
- Honest assessment of where you stand vs. competitors
- Identifying what to learn first and why
- Realistic timelines for skill development

✅ **Career Transition Planning**
- Detailed roadmaps for career pivots
- Understanding what's actually required vs. what you think is required
- Breaking down overwhelming changes into phases

✅ **Tactical Help**
- Resume feedback (with bigger-picture context)
- Interview prep
- Networking strategy
- Job search approach
- LinkedIn profile direction

✅ **Mid-Career Navigation**
- Should I stay or should I go?
- What's actually worth pursuing at my stage?
- Salary negotiation reality check
- Founder/entrepreneur viability assessment

---

## Compatibility with Other Models

### ChatGPT, Claude (via API), Other LLMs

**Short answer:** The `.skill` format only works with Claude.ai and Claude Desktop. Other models cannot use the `.skill` file format.

**But you CAN still use the guidance content:**

1. **Copy-paste the SKILL.md content** into ChatGPT or another LLM
   - Open `SKILL.md` from the GitHub repo
   - Copy all the text
   - Paste it into your ChatGPT system prompt or conversation
   - The instructions will work the same way

2. **What to expect from other models**
   - The guidance structure will still work
   - The quality may vary depending on the model's reasoning ability
   - Claude (in any form) will perform best since the skill was written with Claude's capabilities in mind
   - Some models may be more verbose or less direct

3. **Why skills are Claude-only**
   - Skills are a Claude.ai/Claude Desktop feature designed specifically for those interfaces
   - They allow structured instructions to load conditionally based on user input
   - Other LLM providers have their own systems (GPTs for ChatGPT, custom instructions, system prompts)

**If you want to use this with ChatGPT:**

Go to ChatGPT → Custom GPT → Instructions → paste the entire `SKILL.md` content → save. Then ChatGPT will follow the same guidance structure.

---

## Troubleshooting

### The skill isn't triggering

**Problem:** I'm asking career questions but the skill isn't responding differently.

**Solution:**
- Make sure it's actually loaded (check the skill indicator)
- The skill will auto-trigger on common career phrases — if it's not, try:
  - "I need help with my career"
  - "I want to change careers"
  - More specific prompts tend to trigger better than vague ones

### I'm getting generic advice

**Problem:** The responses feel surface-level, not deeply personalized.

**Solution:**
- The skill *requires* dialogue — it can't personalize without understanding you first
- Give more detailed answers to the initial discovery questions
- Share specifics about your situation, motivations, and constraints
- If Claude is rushing through phases, nudge it: "Can you go deeper on my skill gaps?"

### The skill isn't installed properly

**Problem:** I uploaded it but it doesn't seem to be working.

**Solution:**
- **Claude.ai:** Try uploading again, or refresh the page
- **Claude Desktop:** Make sure the file is in the correct `~/.claude/skills/` folder and restart the app
- **Alternative:** Copy the `SKILL.md` content and paste it into the conversation directly — Claude will still follow the instructions

### I want to use this with ChatGPT/another model

**Solution:** 
- Open the GitHub repo and find `SKILL.md`
- Copy all the text
- In ChatGPT: Settings → Custom Instructions → paste it in the System section
- In other models: Use whatever method that model offers for system prompts/instructions

---

## Tips for Best Results

1. **Be honest in discovery** — The better you answer the initial questions, the better the guidance. "I don't know" is fine; vague answers are not.

2. **Embrace the hard questions** — If Claude asks something uncomfortable ("Are you running away or running toward?"), answer it. That's where the real insight is.

3. **Come back for updates** — Careers evolve. If your situation changes, start a new conversation and update the skill on your new reality.

4. **Share specific context** — Instead of "I'm stuck," say "I'm a 28-year-old frontend engineer, I'm bored with my current role, but I'm afraid of losing income." The more specific, the better.

5. **Use the roadmaps** — The skill will give you concrete monthly plans, resources, and metrics. Actually follow them rather than asking for something different.

---

## What You'll Get (Expected Output)

By the end of a full career guidance session, you should have:

- ✅ A clear understanding of your actual strengths and gaps
- ✅ 2–3 realistic career directions with honest tradeoffs
- ✅ A specific, sequenced skill development plan with timelines
- ✅ A concrete 90-day action plan you can start tomorrow
- ✅ Honest feedback on what you need to stop believing or doing
- ✅ Specific resources (courses, books, people to connect with)
- ✅ Metrics to track your progress

This is not a single-message answer. It's a conversation. Budget 20–40 minutes for a thorough session.

---

## Questions?

If the skill doesn't work as described, or you find edge cases it doesn't handle well, file an issue on the GitHub repo or reach out to the maintainer.

Happy career planning.
