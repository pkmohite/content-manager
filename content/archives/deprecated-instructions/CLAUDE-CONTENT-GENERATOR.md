# Claude Code Content Generator

**Optimized prompts and instructions for generating Proponent content with Claude Code**

---

## 🎯 Quick Content Generation Prompts

### **For LinkedIn Posts (Use when you need 2-3 posts per week)**

#### **Standard Content Generation Prompt**
```
Generate a LinkedIn post for Proponent following these guidelines:

⚠️ ANTI-DUPLICATION CHECK (MANDATORY FIRST STEP):
Before generating content, you MUST:
1. Search /content-manager/CONTENT-MASTER-INDEX.md for similar keywords and themes
2. Review /content-manager/content/drafts/ideas-backlog.md for topic usage status
3. Check content relationship mapping for related content clusters
4. If overlap found, either choose different angle/audience/depth or select different topic
5. Reference similar content to ensure differentiation

CONTEXT:
- I'm Prashant Mohite, CEO/Co-founder of Proponent
- Proponent is an AI-first conversational intelligence platform
- Target audience: VP Sales, Revenue Operations, Product Marketing Managers
- Tone: Conversational, insightful, evidence-based (see my writing style in /content-manager/references/style-references/)

VIRAL OPTIMIZATION REQUIREMENTS:
- Create shareability: Include insights professionals want to share with their networks
- Build reference value: Add frameworks/takeaways readers will save for future use
- Spark discussion: End with questions that encourage meaningful professional debate
- Provide immediate value: Readers should gain actionable insights they can apply within 24 hours
- Challenge convention: Take contrarian positions on accepted industry practices
- Use concrete examples: Include specific scenarios readers can relate to
- Surface hidden truths: Focus on what people discuss privately vs. publicly
- Use creative research: Avoid generic web searches, dig deeper with alternative strategies

CONTENT REQUIREMENTS:
- Use my writing style from published examples in /content-manager/content/published/linkedin-posts/
- Follow content pillars: AI-First Sales Intelligence (30%), Strategy-to-Execution Gap (25%), Founder Insights (20%), Industry Analysis (15%), Customer Intelligence (10%)
- Use varied post structures: frameworks, rants, observations, stories - avoid formulaic patterns
- End naturally: definitive statements, provocative observations, or just stop after the insight
- **NEVER end every post with a question** - this screams AI-generated content
- No hashtags, minimal emojis
- Prioritize value and depth over brevity (300-500 words is fine for valuable frameworks)
- 3-8 short paragraphs with clear structure for mobile scanability
- IMPORTANT: NO MARKDOWN FORMATTING - LinkedIn doesn't support it (no **bold**, no ##headers, no →arrows)
- Use simple bullet points (•) and plain text formatting only

TOPIC: [Specify your topic here, e.g., "Real-time AI coaching vs post-call analysis"]

BEFORE FINALIZING:
- Confirm topic is not marked [USED] in ideas-backlog.md
- Verify unique differentiation from similar content in master index
- Update ideas-backlog.md with [RESERVED] status if selecting from backlog

Create filename as: YYYY-MM-DD-topic-keywords-LINKEDIN-READY.md
Save to: /content-manager/content/drafts/linkedin-drafts/
```

#### **Framework-Based LinkedIn Post Prompt**
```
Create a LinkedIn post featuring a framework or model for B2B sales/marketing professionals.

REQUIREMENTS:
- Original framework with 3-5 levels/stages/categories
- Personal insight from building Proponent
- Actionable takeaways for readers
- Question that encourages professional discussion
- Follow my established writing patterns from existing content

FRAMEWORK TOPIC: [e.g., "The 4 Stages of Sales AI Maturity"]
TARGET AUDIENCE: [Sales Leaders/PMMs/RevOps]

Reference my content strategy in /content-manager/CONTENT-STRATEGY.md
Use templates from /content-manager/content/archives/templates/linkedin-post-template.md
```

### **For Blog Posts (Use when you need 1-2 posts per month)**

#### **Comprehensive Framework Blog Prompt**
```
Generate a comprehensive blog post (3,000+ words) for Proponent thought leadership.

⚠️ ANTI-DUPLICATION CHECK (MANDATORY FIRST STEP):
Before generating content, you MUST:
1. Search /content-manager/CONTENT-MASTER-INDEX.md for similar keywords and themes
2. Review /content-manager/content/drafts/ideas-backlog.md for topic usage status
3. Check existing blog drafts for framework overlap
4. Verify no similar LinkedIn posts cover the same ground at different depth
5. If overlap found, either choose different angle/audience/framework or select different topic

CONTEXT:
- Review my existing blog posts in /content-manager/content/published/blog-posts/
- Follow the framework approach from successful posts like "AI Sales Coaching Hierarchy"
- Target: B2B sales and marketing professionals seeking strategic insights

REQUIREMENTS:
- Create original maturity model, hierarchy, or assessment framework
- Include diagnostic questions for self-assessment
- Provide specific implementation guidance
- Natural Proponent positioning (not promotional)
- SEO-optimized for conversation intelligence keywords
- Viral potential through shareability and practical value
- Include underground insights from whisper networks and private conversations
- Use creative research beyond standard web searches

TOPIC: [Specify framework topic, e.g., "The Revenue Intelligence Maturity Model"]

BEFORE FINALIZING:
- Confirm no similar framework exists in master index
- Verify topic not marked [USED] for blog content in ideas-backlog.md
- Update ideas-backlog.md with [RESERVED] status if selecting from backlog
- Check that framework doesn't duplicate existing LinkedIn framework posts

Create filename as: YYYY-MM-DD-topic-keywords-BLOG-READY.md
Use template from /content-manager/content/archives/templates/blog-post-template.md
Reference content strategy from /content-manager/CONTENT-STRATEGY.md
Save to: /content-manager/content/drafts/blog-drafts/
```

---

## 📚 Key Reference Files for Claude Code

### **Essential Context Files (Always reference these)**
1. `/content-manager/CONTENT-STRATEGY.md` - Strategic positioning and messaging
2. `/content-manager/instructions/linkedin-instructions.md` - LinkedIn guidelines
3. `/content-manager/instructions/blog-instructions.md` - Blog post guidelines
4. `/about_proponent/proponent101_v2.md` - Product understanding
5. `/content-manager/profiles/linkedin-profile-prashant.md` - Personal background

### **Writing Style References**
1. `/content-manager/content/published/linkedin-posts/` - Published LinkedIn examples
2. `/content-manager/content/published/blog-posts/` - Published blog examples
3. `/content-manager/references/style-references/` - Style examples

### **Templates & Frameworks**
1. `/content-manager/content/archives/templates/linkedin-post-template.md`
2. `/content-manager/content/archives/templates/blog-post-template.md`

---

## 🔄 Content Generation Workflow

### **When You Need New Content**

#### **Step 1: Check Content Pipeline**
- Look at `/content-manager/SIMPLE-POSTING-SCHEDULE.md`
- Identify what type of content you need (LinkedIn vs Blog)
- Check content pillar balance in recent posts

#### **Step 2: Creative Research & Topic Discovery**
- **Use Alternative Search Strategies** (not generic "viral content" searches):
  - `site:reddit.com` + specific pain points/complaints
  - `site:news.ycombinator.com` + critique/problems/limitations
  - Search for failure stories, resistance patterns, implementation disasters
  - Look for "what people actually said" vs "overheard in meetings"
  - Search for founder horror stories, tool failures, "wasted money on"
  - Focus on whisper network topics, private conversations, underground realities
- **Reference ideas from**: `/content-manager/content/drafts/ideas-backlog.md`
- **Avoid**: Generic web searches like "trending topics" or "viral content"

#### **Step 3: Use Appropriate Prompt**
- Copy the relevant prompt above
- Customize the topic/focus area based on creative research findings
- Include specific requirements or audience focus

#### **Step 4: Content Review Process**
- Review generated content against your style examples
- Check alignment with content strategy
- Ensure Proponent positioning is natural and valuable
- Make any necessary adjustments

#### **Step 5: File Management**
- **Use Consistent Naming Convention**:
  - **LinkedIn Posts**: `YYYY-MM-DD-topic-keywords-LINKEDIN-READY.md`
  - **Blog Posts**: `YYYY-MM-DD-topic-keywords-BLOG-READY.md`
  - **Date Format**: Use intended publication date
  - **Topic Keywords**: 2-4 descriptive words separated by hyphens
- Save to appropriate drafts folder (`linkedin-drafts/` or `blog-drafts/`)
- Update `/content-manager/SIMPLE-POSTING-SCHEDULE.md` with new content
- Move to published folder after posting (remove `-READY` suffix when published)

---

## 🕵️ Creative Research Methodology

### **Alternative Search Strategies (Use Instead of Generic Web Searches)**

#### **Underground Pain Points Discovery**
```
# Search Examples:
- site:reddit.com "sales AI" OR "conversation intelligence" complaints problems
- "I hate when sales tools" OR "sales AI doesn't work" frustration 
- site:news.ycombinator.com "sales" AND ("LLM" OR "AI") critique limitations
- "founder burning cash on" OR "wasted money on sales tool" disaster
```

#### **Whisper Network Insights**
```
# Search Examples:
- "sales team actually said" OR "overheard in sales meeting" horror stories
- "everyone is talking about" "but nobody says" private conversations
- B2B sales whisper network private reality check
- "what sales reps really think" OR "private slack channels"
```

#### **Implementation Reality Check**
```
# Search Examples:
- "AI sales tool failed" OR "conversation intelligence didn't work" 
- "stopped using AI for sales" OR "removed AI from our process"
- indie hackers sales tool mistake lessons learned wasted
- CRM implementation disaster failure story
```

#### **Founder Horror Stories**
```
# Search Examples:
- site:indiehackers.com "wasted" OR "failed" sales AI tool
- "shiny object syndrome" AI implementation disaster
- founder mistake "sales tool" expensive lesson learned
```

### **Research Output Processing**
1. **Identify Patterns**: What themes emerge across multiple sources?
2. **Find Contradictions**: What do people say publicly vs. privately?
3. **Extract Specific Examples**: Real quotes, data points, specific scenarios
4. **Develop Contrarian Angles**: How does this challenge conventional wisdom?
5. **Create Underground Frameworks**: Structure insights into shareable models

---

## 📅 Content Planning with Claude Code

### **Monthly Content Planning Session**
```
Help me plan content for [Month] based on:

CURRENT CONTEXT:
- Review performance of recent posts in /content-manager/content/published/
- Check content pillar balance from /content-manager/CONTENT-STRATEGY.md
- Use creative research strategies to identify what people are actually discussing
- Look for whisper network insights beyond obvious trending topics

GENERATE:
- 8-12 LinkedIn post topics for the month
- 2 blog post framework ideas
- Content calendar with optimal publishing dates
- Mix of content pillars and audience focuses

CONSIDERATIONS:
- Industry events or trending topics for the month
- Seasonal relevance for B2B buyers
- Content that builds on previous successful posts
```

### **Weekly Content Sprint**
```
Generate 3 LinkedIn posts for this week with these requirements:

WEEK FOCUS: [e.g., "AI implementation challenges"]
CONTENT MIX: 
- 1 Framework/Analysis post (high engagement target)
- 1 Founder insight post (personal authority building)  
- 1 Industry commentary post (thought leadership)

EACH POST SHOULD:
- Target different audience segments (Sales Leaders, PMMs, RevOps)
- Follow established writing style and formatting
- Include engagement-driving elements
- Maintain strategic messaging consistency

Reference recent performance data and adjust topics accordingly.
```

---

## 🎯 Content Performance Optimization

### **Performance Analysis Prompt**
```
Analyze the performance of my recent content and provide optimization recommendations:

ANALYZE:
- Content in /content-manager/content/published/ folders
- Engagement patterns and audience feedback
- Content pillar performance balance
- Topic resonance with target audience

RECOMMEND:
- High-performing content themes to repeat
- Underperforming approaches to adjust
- New topics or angles to explore
- Content format optimizations

GENERATE:
- 3 new content ideas based on top performers
- Adjustments to content strategy if needed
- Next month's content theme recommendations
```

---

## 🚀 Quick Start Commands

### **Emergency Content Generation (Need post today)**
```
I need a LinkedIn post to publish today about [TOPIC]. 

Generate following my style from /content-manager/content/published/linkedin-posts/, targeting [AUDIENCE], focused on [CONTENT PILLAR].

Make it engaging, valuable, and ready to post immediately.
```

### **Week Ahead Planning**
```
Plan my content for next week based on:
- My publishing schedule pattern
- Recent content topics to avoid repetition  
- Current industry trends in B2B sales/AI
- Content pillar balance needs

Generate titles and brief descriptions for 3 LinkedIn posts.
```

---

*This guide optimizes your future content generation with Claude Code by providing specific prompts, context files, and workflows tailored to Proponent's content strategy.*