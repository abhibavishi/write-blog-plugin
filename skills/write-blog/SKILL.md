---
name: write-blog
description: Write SEO-optimized, human-sounding blog posts. Use when the user wants to create, draft, rewrite, or improve blog posts. Triggers on phrases like "write a blog", "blog post about", "rewrite blog", "SEO article", or "content for the blog". Produces formatted HTML content ready for CMS publishing.
---

# SEO Blog Post Writer

Write long-form, SEO-optimized blog posts that read like they were written by a knowledgeable
human -- not an AI. Every post should rank on Google and actually help the reader accomplish
something or understand something deeply.

## Writing Philosophy

This skill follows the Ahrefs editorial approach: authoritative but conversational, data-backed,
scannable, and genuinely useful. The goal is content that earns links and ranks -- not content
that fills a page.

**Core principle:** Write the article you'd want to read yourself. If a section bores you,
it will bore the reader. Cut it or make it useful.

**BLUF (Bottom Line Up Front):** Every section opens with its key takeaway. The first sentence
of each H2 section states the conclusion or main point -- not the setup. Supporting detail,
evidence, and reasoning follow. Apply the first-sentence test: read only the first sentence of
every section. If you can't understand the article, BLUF is missing.

## Before Writing

1. Identify the target keyword and search intent. Ask the user if not provided.
2. Read `references/product-knowledge.md` to understand the product's features, positioning, and terminology.
3. Read `references/style-guide.md` for tone, formatting, and SEO patterns.
4. If the topic relates to a product feature, explore source code to verify actual product behavior. Do not guess.
5. Consider what currently ranks for the target keyword. The post must be more useful, more specific, and better structured than existing results.

## Context Gathering

Before drafting, establish with the user:

- What is the target keyword or topic?
- Who is the target reader?
- What search intent does this serve? (informational, comparison, how-to)
- Should the product be mentioned as a tool recommendation? If so, how prominently?
- Are there specific competitors to compare against?
- What's the approximate target word count? (default: 2000-3000 words)

Do not ask all questions at once. Start with the most important 2-3 and follow up as needed.

## Post Structure

Every blog post follows this ordered structure. Adapt sections based on post type
(listicle, how-to, comparison, guide) but maintain the overall flow.

### 1. Title

Format depends on post type:

| Post Type | Title Format | Example |
|-----------|-------------|---------|
| How-to | How to [Verb] [Thing] ([Qualifier]) | How to Write LinkedIn Posts That Actually Get Engagement |
| Listicle | [Number] Best [Things] for [Year] [Qualifier] | 7 Best Comment Generators for 2026 (Free + Paid) |
| Comparison | [Thing A] vs [Thing B]: [What Matters] | Product A vs Product B: Which Tool Is Right for You? |
| Guide | [Topic]: [Promise] | LinkedIn SEO: The Complete Guide to Getting Found |
| Data/study | We Analyzed [X]: Here's What We Found | We Analyzed 10,000 Posts: Here's What Gets Engagement |

Rules:
- Include the target keyword near the beginning of the title
- Keep under 60 characters when possible (for SERP display)
- Include the current year for comparison/listicle posts
- Use brackets for qualifiers: [Free], [With Examples], [+ Templates]

### 2. Introduction (2-4 short paragraphs)

Use the PAS formula (Problem-Agitate-Solve):

1. **Problem** (1-2 sentences): State the reader's challenge directly. No preamble.
2. **Agitate** (1-2 sentences): Make the problem feel real. Use a specific scenario, stat, or consequence.
3. **Solve** (1-2 sentences): Position this article as the answer. Preview what they'll learn.

Rules:
- NEVER start with "In this article..." or "In today's digital age..." or dictionary definitions
- Open with the problem, a surprising stat, or a bold claim
- Establish credibility early ("we tested", "after analyzing", "in our experience")
- End the intro with a brief preview of what the article covers
- Keep the entire intro under 100 words

**Good intro:**
> Commenting on LinkedIn posts is one of the fastest ways to grow your network. But most
> comments -- "Great post!" and "Thanks for sharing!" -- get scrolled past without a second
> glance.
>
> The difference between a comment that builds your reputation and one that wastes your time
> comes down to a few specific techniques. Here are 7 strategies that consistently get replies,
> profile views, and new connections.

**Bad intro:**
> In today's digital age, LinkedIn has become an indispensable platform for professionals.
> With millions of users, standing out can be challenging. In this comprehensive guide, we
> will walk you through everything you need to know about commenting effectively.

### 3. Body Content

**BLUF rule:** The first sentence of every H2 section states the key takeaway or conclusion.
Do not build up to the point -- lead with it. Evidence, steps, and context follow.

**BLUF examples:**

Good (takeaway first):
> **Ahrefs has the most accurate keyword data** because it crawls the web more frequently than
> any competitor. In our tests across 500 keywords, freshness beat Semrush by 23%...

Bad (buried lead):
> Keyword research tools have been around for years. Many options exist. Ahrefs, Semrush, and
> Moz all claim accuracy. After extensive testing, we found Ahrefs to be the most accurate...

Structure depends on post type:

**Listicle posts:**
- Each item gets an H2 heading with the item number
- Under each H2: 1-2 paragraph description, key features/pros/cons, pricing if relevant
- Use H3s for sub-sections (Best for, Pros, Cons, Pricing)
- Include a comparison table summarizing all items after the list or at the top

**How-to posts:**
- Each step gets an H2 heading with a number
- Steps use imperative verbs ("Open", "Click", "Write", "Choose")
- Include specific examples, not just instructions
- Show what success looks like after each major step

**Guide/explainer posts:**
- H2s cover major concept areas
- Build from fundamentals to advanced topics
- Each section is self-contained (reader might jump to it via TOC)

### 4. Product Integration (when applicable)

Product mentions should feel like a natural part of the content, not a sales pitch.
Refer to `references/product-knowledge.md` for positioning and messaging guidelines.

**Do:**
- Mention the product as one option among several when listing tools
- Show how the product solves a specific problem discussed in the article
- Use product-led examples: "For example, with [Product] you can..."
- Keep product mentions to 1-2 per article unless it's a product-focused post

**Do not:**
- Make the entire article a product advertisement
- Use superlatives like "the best" or "the ultimate" when referring to the product
- Include pricing details that will go stale (link to pricing page instead)
- Force a product mention into topics where it's not relevant

### 5. Conclusion (1 short paragraph)

- Summarize the key takeaway in 1-2 sentences
- End with a forward-looking statement or actionable next step
- No "In conclusion..." or "To sum up..."
- Keep under 50 words

### 6. FAQ Section (optional, recommended for SEO)

- 3-5 questions that people actually search for
- Keep answers to 2-3 sentences each
- Use the exact phrasing people would type into Google
- These target featured snippet opportunities

## Writing Rules

### Voice and Tone

- **Conversational authority**: Write like a smart colleague explaining something, not a textbook
- **First person is fine**: Use "I" for personal experience, "we" for company perspective
- **Second person for the reader**: "you" throughout -- talk directly to them
- **Opinionated when earned**: Back opinions with data or experience
- **No hedging**: Say "This works because..." not "This might potentially work because..."

### Readability

- **Paragraphs**: 1-3 sentences max. Break aggressively.
- **Sentences**: Vary length. Short punchy sentences between longer ones. Never more than 25 words.
- **Words**: Use simple words. "Use" not "utilize". "Start" not "commence". "Help" not "facilitate".
- **Transitions**: Natural connectors between sections, not formulaic ("Moving on to...")

### Formatting

- **Bold** for key terms, tool names, and important takeaways
- **H2** for major sections (numbered in listicles/how-tos)
- **H3** for sub-sections within an H2
- **Bullet lists** for features, pros/cons, quick tips
- **Numbered lists** for sequential steps only
- **Tables** for comparisons (tools, pricing, features)
- **Code blocks** for prompts, templates, or examples the reader should copy

### SEO

- Target keyword appears in: title, first 100 words, 1-2 H2s, naturally throughout
- Use semantic variations and related keywords -- never stuff the exact phrase
- Write for humans first, search engines second
- Internal links: mention other blog posts or docs when relevant
- Every H2 should work as a standalone answer (for featured snippets)

### What to Avoid

- "In today's digital age" or any variation of this opening
- "In this comprehensive guide" or similar meta-references
- "Utilize", "leverage", "synergy", "paradigm", "cutting-edge"
- "Simply", "just", "easy" -- respect that things can be hard
- Passive voice when active is possible
- Filler paragraphs that don't add information
- Repeating the same point in different words
- Marketing superlatives ("revolutionary", "game-changing", "ultimate")
- Dictionary definitions as section openers
- Emojis (unless the user explicitly requests them)
- Generic stock-photo descriptions

## Output Format

The output should include:

1. **Title**: Plain text
2. **Short Description**: 1-2 sentence meta description (under 160 characters)
3. **Date**: Format as "DD Mon YYYY" (e.g., "12 Feb 2026")
4. **Read Time**: Estimate based on ~200 words/minute, format as "X mins read"
5. **Keywords**: Comma-separated target keywords
6. **Content**: HTML-formatted body content

### HTML Content Formatting

Use these standard HTML elements:

```html
<h2>Section Heading</h2>
<h3>Sub-heading</h3>
<p>Paragraph text with <strong>bold</strong> and <em>italic</em> formatting.</p>
<ul>
  <li>Bullet point</li>
</ul>
<ol>
  <li>Numbered item</li>
</ol>
<pre><code>Code block or prompt template</code></pre>
```

Note: Check `references/product-knowledge.md` for any CMS-specific heading adjustments
(some CMS platforms reserve h1/h2 for page templates).

## Quality Checklist

Before presenting a post to the user, verify every item:

- [ ] Title includes target keyword and follows the format for its post type
- [ ] Introduction uses PAS formula and is under 100 words
- [ ] No "In today's digital age" or similar cliche openings
- [ ] BLUF test: read only the first sentence of every H2 section -- the article should be understandable from those sentences alone
- [ ] Every section adds unique value -- no filler
- [ ] Paragraphs are 1-3 sentences max
- [ ] Bold is used for key terms and tool names
- [ ] Tables are used for any comparison of 3+ items
- [ ] Product mentions feel natural, not forced
- [ ] Target keyword appears in title, intro, and 1-2 headings
- [ ] Conclusion is under 50 words with a clear takeaway
- [ ] Read time is calculated and included
- [ ] Short description is under 160 characters
- [ ] No emojis unless explicitly requested
- [ ] Content reads like a human wrote it -- read it aloud to check
- [ ] Every claim is backed by data, example, or clear reasoning
