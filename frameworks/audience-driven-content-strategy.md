# Audience-Driven Content Strategy

Keyword research alone tells you who is searching. Inquiry data tells you who is buying. The gap between the two is the highest-leverage content opportunity for B2B clients.

This methodology was developed during a tech-led.com engagement and applies to any B2B client with structured inquiry data: contact form submissions, CRM records, sales conversation notes, RFQ logs, or chat transcripts.

## When This Methodology Fits

Use audience-driven content strategy when:

- the client is B2B with technical or specialized buyers
- the client has accumulated inquiry data (contact forms, CRM, sales notes) for at least 3-6 months
- Google Search Console reveals impressions and rankings on a meaningful query set
- the buyer's language in inquiries differs from generic keyword tools' language
- the client suspects, or has confirmed, that real customers are not arriving through expected SEO queries

Use traditional keyword research when:

- the client is early-stage with no inquiry history
- the buyer is a broad consumer audience with predictable search vocabulary
- the goal is brand discovery rather than buyer conversion
- the client lacks a CRM or structured contact form

This framework complements, not replaces, keyword research. Run both in parallel where possible.

## The Four-Step Method

### Step 1: Extract Audience Clusters from Inquiry Data

Pull every inquiry record available: contact form submissions, CRM entries, sales notes, RFQs. Normalize the fields you care about:

- company name
- company type (Manufacturer, University/Research, Hospital, Government Lab, Reseller, Individual)
- industry / vertical
- stated application or use case
- country
- inquiry message (verbatim)
- date

Cluster the records along several axes:

- by company type
- by industry
- by application
- by country or region
- by repeat sender or repeat company

Document the top 8-12 clusters with inquiry counts. The clusters become the audience taxonomy for the rest of the work.

### Step 2: Identify Buyer Queries from Inquiry Messages

Inquiry messages contain the buyer's verbatim language: what they were trying to do, what specs they needed, what problem they were solving, what they tried before contacting the client. This is the real audience vocabulary, and it is almost always more specific than what keyword tools return.

For each cluster, extract:

- the application or job to be done, in the buyer's words
- the specs they cite (wavelengths, materials, dimensions, models)
- the comparisons they make (X vs Y phrasing)
- the questions they ask
- the alternatives they considered

Save the verbatim quotes. They become the source language for article briefs, FAQ entries, and PDP copy.

### Step 3: Cross-Reference with Google Search Console

Pull GSC queries in position 2-20 over a 3-month window. Position 1 is already winning; below position 20 is too speculative. The 2-20 range is the realistic optimization band.

Bucket each GSC query into the same audience clusters from Step 1.

Build a cross-reference matrix:

| Audience Cluster | Inquiry Count | GSC Queries (2-20) | GSC Impressions | Status |
|---|---|---|---|---|
| [Cluster] | [Count] | [Count] | [Impressions] | [Tier] |

The matrix exposes three patterns:

- **clusters with both inquiry demand and GSC presence**: existing rankings to push to page 1
- **clusters with inquiry demand and no GSC presence**: territory to claim
- **clusters with GSC presence and no inquiry demand**: may indicate wrong-audience traffic or top-of-funnel that hasn't converted yet (escalate to traffic-vs-inquiry triage)

### Step 4: Build the Content Priority List

Organize the work into three tiers:

**Tier 1 - GSC momentum + inquiry demand.** Existing rankings are within reach of page 1, and inquiry data confirms the audience converts. Highest ROI. Optimize, don't rewrite.

**Tier 2 - inquiry demand but no GSC presence.** Real buyers exist but the site has no claim on the query. Build new content tuned to the audience's verbatim language and link it from existing pillars.

**Tier 3 - opportunistic.** Promising clusters with thin data on either side. Validate with DataForSEO before committing build effort.

Each tier-1 and tier-2 article should follow the "[Solution] for [Audience]" format below.

## The "[Solution] for [Audience]" Article Format

Inquiry-driven articles work best when the title binds a specific solution to a specific audience.

Examples:

- "NIR LEDs for fNIRS Research"
- "SWIR LEDs for Hyperspectral Imaging Systems"
- "660nm and 940nm LEDs for Pulse Oximetry Design"
- "UV LEDs for Wafer Inspection"

This format:

- matches how buyers ask questions in inquiries
- matches how technical buyers query AI systems
- pre-qualifies the reader so the page can speak to one audience with precision
- creates a natural home for application-specific spec recommendations, product links, and FAQs

Article structure:

1. Direct answer paragraph: which products, in one short paragraph
2. Why this audience needs this solution (the application context)
3. Spec table tuned to the audience (wavelength, FWHM, package, etc.)
4. Product recommendations linked to the catalog
5. Comparison or alternatives (X vs Y within the audience context)
6. FAQs reusing verbatim inquiry language
7. Related guides and pillar links

## Template: Audience Cluster Analysis

```
Cluster: [name]
Inquiry count: [count]
Period: [date range]

Company type breakdown:
- [type]: [count]
- [type]: [count]

Industry breakdown:
- [industry]: [count]

Top applications cited:
- [application]: [count]

Geography:
- [country]: [count]

Verbatim language samples:
- "[quote]"
- "[quote]"

Specs cited:
- [spec]

Comparisons made:
- [X vs Y]

Open questions raised by buyers:
- [question]
```

## Template: Cross-Reference Matrix

```
| Audience Cluster | Inquiry Count | GSC Query Count (pos 2-20) | GSC Impressions | Top GSC Queries | Inquiry/GSC Status | Tier |
|---|---|---|---|---|---|---|
| [cluster] | [n] | [n] | [n] | [list] | [Both / Inquiry-only / GSC-only] | [1/2/3] |
```

## Worked Example: Tech-led.com

The tech-led engagement processed roughly 350 inquiries from contact form data and CRM exports.

Audience clusters that emerged (representative, not exhaustive):

- medical / biomedical device OEMs
- fNIRS researchers (largely university)
- university and research labs (broader than fNIRS)
- machine vision integrators
- multispectral imaging system designers
- security and night vision integrators
- semiconductor and wafer inspection
- UV curing and fluorescence applications
- agriculture and food inspection (SWIR-driven)

Patterns from the cross-reference:

- **Tier 1**: 365nm, 405nm, 850nm, 940nm, 660nm, 1450nm, 1550nm wavelength queries. Already ranking position 5-9 with meaningful impressions. Goal: push to page 1.
- **Tier 2**: fNIRS, pulse oximetry design, hyperspectral imaging, multispectral arrays. Strong inquiry demand, near-zero GSC presence. Goal: claim new territory with "[Solution] for [Audience]" articles.
- **Tier 3**: SWIR food / agriculture inspection, custom multi-wavelength modules. Mixed signal. Validate before committing.

The resulting article priority list folded into a four-pillar architecture: UV LED Guide, NIR LED Guide, SWIR LED Guide, and Multispectral LED Systems, with application-specific articles clustered beneath each.

## Open Questions for Future Engagements

- how to handle clusters where inquiry vocabulary uses internal jargon that buyers will never search
- how to weight repeat-customer inquiries vs single-touch inquiries when sizing clusters
- when to escalate a GSC-only cluster to traffic-vs-inquiry triage (see future framework entry)
- how to handle multi-language inquiry data without distorting US-English GSC signal

## Related Frameworks

- [Comparison Page Strategy](./comparison-page-strategy.md) — the article format that most often serves Tier 1 wavelength selection content
- [SEO, AEO, and GEO Model](./seo-aeo-geo-model.md) — the layered model this strategy feeds into
- [AI Visibility Tracking](./ai-visibility-tracking.md) — the prompt set should be seeded from inquiry clusters, not generic queries
