# Tier 2: Content Types

Tier 1 covers the signals all content shares. Tier 2 adjusts for format.

Different content types serve different reader intents — and different extraction behaviors. A blog post, a FAQ page, a local landing page, and a product page each need different structural choices to perform well in answer engines. Pick the module that matches your content format and add it after the Tier 1 prompt.

Use one or two modules per piece of content. Using all four at once creates conflicting instructions.

---

## How to use these modules

1. Start with the full Tier 1 Foundation prompt
2. Choose the module below that matches your content type
3. Copy that module's prompt block
4. Paste it directly below your Tier 1 prompt in your AI tool
5. Add your content at the very bottom under `=== SUPPLIED COPY ===`
6. Run the combined prompt

If using two modules (e.g. A + B), paste both below Tier 1 in sequence — then add your content last.

---

## Module A: Featured Snippet Optimization

Use when your content answers a specific question and you want it selected as the direct answer at the top of search results.

```
FEATURED SNIPPET OPTIMIZATION:

Identify the single primary question this content answers.

Place a 42-50 word paragraph answer directly below the H2 that poses 
that question. This answer must:
- Be complete without surrounding context
- Use declarative sentences, not fragments
- Avoid first-person ("I" or "we")
- Not begin with the heading text repeated

For process or step-by-step content:
- Use numbered lists (3-8 items)
- Each item: 1-2 sentences maximum
- Begin each item with an action verb

For comparison content:
- Use a table with 2-4 columns and no more than 5 rows
- Include a clear winner or recommendation where appropriate

Add at least one "What is [topic]?" section and one "How to [action]?" 
section if not already present.
```

---

## Module B: FAQ / People Also Ask Optimization

Use when your content covers multiple related questions, or when you want to capture the expandable question clusters that appear in Google search results.

```
FAQ / PEOPLE ALSO ASK OPTIMIZATION:

Generate 5-8 questions a reader would ask about this topic.

Format each as an H3 heading phrased as a natural question.
Place a 40-60 word direct answer immediately below each heading.

Requirements:
- Cluster questions by subtopic — don't mix unrelated questions
- Include questions from different stages of reader intent:
  * Awareness questions ("What is...?")
  * Consideration questions ("How does...?" "What's the difference between...?")
  * Decision questions ("Which should I...?" "Is X worth it?")
- Answers must be self-contained — no "As mentioned above..."
- Each answer should introduce at least one entity (name, brand, statistic)

Add a dedicated FAQ section at the end of the content using this 
same format, separate from the inline question headings.
```

---

## Module C: Local Search Optimization

Use when the content targets an audience in a specific geographic area, or when the product or service is location-dependent.

```
LOCAL SEARCH OPTIMIZATION:

Geographic targeting requirements:
- Include the city or region name in the H1
- Include the city or region name in at least one H2
- Reference specific local landmarks, neighborhoods, or geographic 
  details where natural — not forced
- Include natural "near me" language variations in at least one paragraph

Service area requirements (for B2C content):
- State the service area explicitly in the first 100 words
- Include a dedicated section titled "Areas We Serve" or equivalent
- List specific cities, zip codes, or neighborhoods served

Entity requirements:
- Name the business, practice, or organization in full on first mention
- Include address or general location if relevant
- Reference local context (events, institutions, geography) to signal 
  genuine local relevance rather than templated local SEO
```

---

## Module D: Product and Service Page Optimization

Use when the content's primary goal is to convert a reader evaluating a specific product or service.

```
PRODUCT / SERVICE PAGE OPTIMIZATION:

Structure requirements:
- Lead with the primary benefit, not the feature
- Include a comparison table: your offering vs. 1-2 alternatives
  (features, pricing, key differentiators)
- Add a pros/cons section — honest cons improve credibility and 
  reduce bounce from unqualified visitors
- Include a FAQ section addressing the 5 most common objections 
  or questions before purchase

Content requirements:
- Every claim about performance or results must include a source 
  or specify "based on customer data" / "based on internal testing"
- Include at least one specific use case or customer scenario
- State the intended audience explicitly ("This is for teams that...")
- Include a clear, single call to action — do not offer multiple 
  competing next steps on the same page

Schema signals:
- Flag any pricing information for schema markup (Product schema)
- Flag any review or rating content for schema markup (Review schema)
- Flag FAQs for schema markup (FAQPage schema)
  Note: Schema markup is added in your CMS or HTML, not in the copy itself.
  See your platform documentation for implementation.
```

---

## Choosing the right module

| Content type | Recommended module |
|---|---|
| Blog post answering one main question | Module A |
| Resource page or knowledge base article | Module B |
| City or regional landing page | Module C |
| Product page or service description | Module D |
| Long-form guide covering multiple questions | Modules A + B |
| Local service business page | Modules C + D |

---

*Next: [Tier 3 — Platforms](tier-3-platforms.md)*
