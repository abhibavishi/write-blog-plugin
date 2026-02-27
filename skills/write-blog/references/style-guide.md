# Blog Style Guide -- Ahrefs-Inspired

This reference defines the editorial voice and formatting patterns for all blog posts.
Based on analysis of top-performing SEO content from Ahrefs, Backlinko, and similar
content-led SaaS companies.

## The Ahrefs Formula (Condensed)

1. Pick a proven topic with search demand
2. Match search intent by analyzing what currently ranks
3. Open with a tight PAS intro (2-3 paragraphs max)
4. **Open every section body with BLUF -- state the key takeaway first, then support it**
5. Structure with numbered, descriptive H2s that form a standalone outline
6. Write in short, conversational paragraphs (1-3 sentences)
7. Back every claim with data, examples, or clear reasoning
8. Use real examples with specifics (actual tools, actual numbers, actual scenarios)
9. Integrate the product naturally as part of the solution, not as a pitch
10. Break up text aggressively with bullets, bold, images, callouts, tables, and sub-headings
11. End briefly -- no bloated conclusions

## BLUF: Bottom Line Up Front

Every H2 section body starts with the conclusion -- not the setup.

**Structure:**
1. First sentence: the takeaway (what the reader should know, do, or conclude)
2. Following sentences: the reasoning, evidence, examples, or steps

**First-sentence test:** Read only the first sentence of every section. If you can't understand
the article from those sentences alone, BLUF is missing.

**Why it works for humans:** Nielsen Norman Group's eye-tracking research shows people read in
an F-pattern -- heavy focus at the top, sharp drop in the middle. If the takeaway is buried in
paragraph 3, most readers won't see it.

**Why it works for LLMs:** Models show a U-shaped attention bias -- they overweight the
beginning of a text. Putting the answer first makes content easier to retrieve, embed, and cite.

### BLUF Examples

**Good (takeaway first):**
> Ahrefs has the most accurate keyword data because it crawls the web more frequently than any
> competitor. In our tests across 500 keywords, it outperformed Semrush by 23% on data
> freshness...

**Bad (buried lead):**
> Keyword research tools have been around since the early days of SEO. Many tools claim to have
> the most accurate data. Ahrefs, Semrush, and Moz are the most popular. After testing
> extensively, we found that Ahrefs is the best option...

**Good (how-to section):**
> The fastest way to find low-competition keywords is to filter by Keyword Difficulty below 20
> and search volume above 500. Here's how to do it in Ahrefs...

**Bad (how-to section):**
> Keyword difficulty is a metric that tells you how hard it is to rank. There are many factors
> involved. Search volume also matters. To balance these, you'll want to...

## Sentence Patterns

**Vary sentence length to create rhythm:**

> Short sentence. Then a longer one that explains or expands on the idea with more
> detail. Back to short. Medium-length for balance. Then punch it home.

**Use sentence fragments for emphasis (sparingly):**

> Most comments add nothing. Zero value. That's why they get ignored.

**Transition naturally, not formulaically:**

Good: "But here's where most people go wrong."
Bad: "Now let's move on to discuss the next important point."

Good: "That said, there's a catch."
Bad: "Having discussed the above, we will now explore another aspect."

## Heading Patterns

**Listicle H2s:**
```
1. [Tool Name] -- [One-line value prop]
2. [Tool Name] -- [One-line value prop]
```

**How-to H2s:**
```
1. [Verb] [thing] ([optional qualifier])
2. [Verb] [thing]
```

**Guide H2s:**
```
What is [concept]?
Why [concept] matters for [audience]
How to [apply concept] (step by step)
[Number] [tips/strategies] for [better results]
```

## Comparison Table Template

When comparing tools, always include a summary table:

```html
<table>
  <thead>
    <tr>
      <th>Tool</th>
      <th>Best For</th>
      <th>Starting Price</th>
      <th>Free Plan</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Tool Name</strong></td>
      <td>One-line use case</td>
      <td>$X/mo</td>
      <td>Yes/No</td>
    </tr>
  </tbody>
</table>
```

## Intro Formulas

### PAS (Problem-Agitate-Solve) -- Default

```
[State the problem in 1-2 sentences]

[Make it worse -- consequence, stat, or relatable scenario in 1-2 sentences]

[This article is the solution. Preview what they'll learn in 1-2 sentences]
```

### PSP (Problem-Solution-Proof) -- For authority pieces

```
[State the problem]

[Give the solution upfront]

[Prove you know what you're talking about -- data point, result, credential]
```

### Hook-Story-Offer -- For experience-based posts

```
[Surprising stat or bold statement]

[Brief personal experience or observation that backs it up]

[What this article covers]
```

## CTA Patterns

### In-content (subtle, product as tool recommendation)
> If you want to automate this process, tools like **[Product]** let you [specific action]
> directly from [specific context].

### End-of-section (slightly more direct)
> **[Product]** does this automatically -- it [specific feature] so you can [benefit].
> [Link to relevant feature page]

### End-of-article (brief, not pushy)
> Want to put these strategies into practice? [Product]'s [feature] helps you [specific benefit].
> Try it free at [link].

## Words and Phrases to Avoid

| Instead of | Use |
|-----------|-----|
| utilize | use |
| leverage | use, apply |
| facilitate | help, enable |
| commence | start, begin |
| in order to | to |
| at this point in time | now |
| due to the fact that | because |
| a large number of | many |
| in the event that | if |
| prior to | before |
| subsequent to | after |
| endeavor | try |
| optimal | best |
| paradigm | (cut entirely) |
| synergy | (cut entirely) |
| cutting-edge | (cut entirely or be specific) |
| game-changing | (cut entirely or be specific) |
| revolutionary | (cut entirely or be specific) |

## Opening Lines to Never Use

- "In today's digital age..."
- "In the ever-evolving world of..."
- "In this comprehensive guide..."
- "[Topic] is an important part of..."
- "Have you ever wondered..."
- "According to the dictionary, [term] means..."
- "It's no secret that..."
- "As we all know..."
- "In the bustling world of..."

## Formatting Quick Reference

| Element | When to Use |
|---------|------------|
| **Bold** | Tool names, key terms, important stats, takeaway phrases |
| *Italic* | Book titles, emphasis on a single word, introducing a term |
| `Code` | Prompts, templates, anything the reader should copy |
| > Blockquote | Expert quotes, example text, important callouts |
| --- | Section breaks (use sparingly) |
| Tables | Comparing 3+ items on 2+ dimensions |
| Bullet lists | Non-sequential items, features, pros/cons |
| Numbered lists | Sequential steps only |

## Content Depth Benchmarks

| Post Type | Target Word Count | Sections (H2s) | Examples per Section |
|-----------|------------------|-----------------|---------------------|
| Listicle (tools) | 2500-4000 | 7-12 items | 1 per item minimum |
| How-to guide | 2000-3000 | 5-9 steps | 1-2 per step |
| Comparison | 2000-3000 | 5-8 sections | 2+ per tool |
| Beginner's guide | 3000-5000 | 6-10 concepts | 1-2 per concept |
| Data/research | 2000-3000 | 4-6 findings | Charts/numbers throughout |
