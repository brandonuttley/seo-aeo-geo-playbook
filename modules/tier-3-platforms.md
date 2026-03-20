# Tier 3: Platforms

Tier 3 targets specific AI platforms. Use these modules when you have a clear reason to optimize for a particular system — not as a default addition to every piece of content.

The two modules here cover different AI behaviors. ChatGPT and Perplexity prioritize source citation and credibility signals. Google AI Overviews draw heavily from content that already ranks organically, with additional weight on structured formatting and E-E-A-T signals (Experience, Expertise, Authoritativeness, Trustworthiness).

Add one Tier 3 module after completing Tier 1 and your chosen Tier 2 module.

---

## Module A: ChatGPT and Perplexity Citation Optimization

Use when your primary goal is being cited or referenced in AI-generated responses on ChatGPT (with Browse enabled) or Perplexity.

These systems synthesize across multiple sources and select content based on credibility, specificity, and entity clarity. Princeton research found that content applying these signals appeared in AI responses 30-40% more often than unsourced content.

```
GENERATIVE ENGINE OPTIMIZATION (GEO) — ChatGPT / Perplexity:

Source citation requirements:
- Every major claim must be backed by a named source
- Format: "According to [Organization or Author], [claim]."
- Include the publication year where available
- Favor primary sources: research institutions, government data, 
  named industry reports, peer-reviewed studies

Expert attribution requirements:
- Include 2-3 quotes or named perspectives from recognized authorities
- Format: Full name, title, organization, and the attributed statement
- Avoid anonymous attribution ("industry experts say...")

Statistical density requirements:
- Include at least 5 specific statistics with units and dates
- Pair each statistic with its source
- Include at least one comparison statistic ("X vs. Y" or "up from Z%")

Entity requirements:
- Use proper nouns throughout: specific names, branded terms, 
  product names, organization names, geographic locations
- Avoid vague references ("a major tech company") — name the entity
- Define acronyms and technical terms on first use, then use consistently

Freshness signals:
- Include at least one date reference ("as of 2026," "in Q1 2026")
- Reference recent developments or updates where relevant
- Avoid evergreen language that signals outdated content 
  ("in recent years," "increasingly," "more and more")

Structure for citability:
- Each paragraph should contain one citable claim
- Claims should stand alone when extracted from surrounding context
- Avoid burying key facts in the middle of dense paragraphs
```

---

## Module B: Google AI Overviews Optimization

Use when your primary goal is appearing in the AI-generated summary that Google places above traditional search results.

Google AI Overviews draw primarily from content that already ranks in the top 10 organic results for a query. Strong traditional SEO is a prerequisite — this module amplifies content that's already performing, not a substitute for it.

```
AI OVERVIEW OPTIMIZATION — Google:

Organic ranking prerequisite:
- This module works best on content already ranking in positions 1-10
- If content is not yet ranking, prioritize Tier 1 SEO signals first
- AI Overviews rarely surface content from page 2 or beyond

Structural requirements:
- Include a comparison table for any content covering multiple 
  options, products, or approaches
- Add a pros/cons section for product or service content
- Use schema-friendly formatting: structured lists, clear definitions,
  labeled sections
- Place the most important answer in the first 100 words of the content

E-E-A-T signal requirements:
(Experience, Expertise, Authoritativeness, Trustworthiness)
- Include author credentials or publication context near the top
- Reference firsthand experience where applicable 
  ("In our testing..." "Based on our analysis...")
- Cite authoritative external sources — not just internal links
- Include a last-updated date if the content is refreshed periodically

Content format requirements:
- Use clear "What is X?" and "How does X work?" sections
- Format step-by-step processes as numbered lists
- Use tables for any data with 2 or more comparable dimensions
- Keep sentences in key sections under 20 words — 
  AI Overviews extract short, clean statements more reliably than 
  complex sentences

Schema flags (for implementation in your CMS):
- Article schema: author, publish date, organization
- FAQPage schema: question-and-answer pairs
- HowTo schema: step-by-step process content
- Product schema: pricing, availability, ratings
```

---

## Platform behavior reference

| Platform | Primary signal | Content priority | Click behavior |
|---|---|---|---|
| ChatGPT (Browse) | Source credibility | Named citations, statistics | Low — synthesizes without clicking |
| Perplexity | Source diversity | Multiple authoritative sources | Medium — shows sources inline |
| Google AI Overviews | Organic ranking + structure | E-E-A-T, formatted content | Low — summarizes above results |
| Microsoft Copilot | Bing index + credibility | Similar to ChatGPT signals | Low to medium |

**Important note on click behavior:** AI systems generally reduce click-through to source content. Being cited or synthesized builds brand visibility and topical authority — but it does not reliably drive direct traffic. Optimize for GEO when awareness and credibility matter. Optimize for traditional SEO when traffic volume is the primary goal.

---

## A note on stability

GEO signals are less stable than SEO or AEO signals. Platform behavior changes as models are updated, as sourcing policies evolve, and as the volume of AI-optimized content grows.

Treat these modules as hypotheses, not fixed rules. Test. Observe. Update.

The prompts in this module will be revised as platform behavior changes.

---

*Back to: [Framework](../framework.md)*  
*See also: [Combined Examples](../prompts/combined-examples.md)*
