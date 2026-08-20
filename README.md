# SEO Competitor Intelligence

Turn competitor websites into actionable SEO strategies with an AI-powered Agent Skill.

**SEO Competitor Intelligence** helps AI agents analyze publicly available competitor-web evidence and turn it into practical SEO opportunities, content ideas, and prioritized roadmaps.

## Current Version

**0.2.2**

---

## What does it do?

Give your AI agent a competitor website and ask it to analyze the site's SEO strategy.

For example:

> Analyze https://example.com for SEO.
> Identify its main topic clusters, search intent, content gaps,
> competitive strengths, and the top SEO opportunities.

The Skill can turn public website evidence into:

- Website architecture analysis
- Topic and keyword intelligence
- Search-intent analysis
- Competitor strengths and weaknesses
- Content-gap analysis
- SEO opportunity prioritization
- Content recommendations
- Internal-linking opportunities
- 30/60/90-day SEO roadmap

---

## Why use it?

Traditional competitor research often means manually reviewing dozens or hundreds of pages.

This Skill provides a structured framework for turning competitor research into actionable SEO strategy.

Instead of asking:

> "What is my competitor doing?"

You can ask:

> "What should I do next?"

The workflow is designed to distinguish:

1. **Observed evidence**
2. **Analytical inference**
3. **Strategic recommendation**

This prevents assumptions from being presented as verified facts.

---

## Key Features

### Website Architecture

Understand how a competitor organizes its website:

- Page types
- URL patterns
- Categories
- Product/service pages
- Guides and blog content
- Comparison pages
- Scalable landing-page patterns
- Navigation structures
- Content hubs

### Topic & Keyword Intelligence

Identify recurring topics, keyword themes, and content clusters from publicly observable website evidence.

Keyword themes are not automatically treated as verified ranking keywords.

Search volume and ranking positions are not fabricated when reliable evidence is unavailable.

### Search Intent

Classify important topics into:

- Informational
- Commercial Investigation
- Transactional
- Navigational
- Mixed

Intent classifications are analytical judgments supported by observable evidence.

### Content Gap Analysis

Identify topics and content opportunities that appear strategically important but are weakly covered or missing in the competitor landscape.

The framework distinguishes:

- Genuine content gaps
- Weak coverage
- Different coverage
- Poor search-intent alignment
- Opportunities requiring further validation

---

## Opportunity Scoring

Prioritize SEO opportunities using four strategic dimensions:

- Business Value
- Search Intent Value
- Competitive Gap
- Strategic Value

Each dimension uses a 1–5 scale.

### Strategic Priority Score

The Strategic Priority score is:

Business Value
+ Search Intent Value
+ Competitive Gap
+ Strategic Value
= Strategic Priority

The maximum Strategic Priority score is 20.

The score is an internal strategic prioritization framework.

It does not represent:

- Google ranking probability
- Search volume
- Traffic potential
- Revenue potential
- Conversion probability

### Implementation Effort

Implementation Effort is evaluated separately using a 1–5 scale:

- 1 = Very easy
- 2 = Easy
- 3 = Moderate
- 4 = Difficult
- 5 = Very difficult

Implementation Effort must not be subtracted directly from Strategic Priority.

A high-value opportunity with high execution effort should not automatically be considered low priority.

Instead, Strategic Priority and Implementation Effort are used together to determine implementation sequencing.

---

## Implementation Sequencing

### Tier 1 — Immediate Opportunities

Characteristics:

- High Strategic Priority
- Low or Moderate Implementation Effort
- Limited dependencies
- Clear business relevance

These opportunities should generally be executed first.

### Tier 2 — Strategic Projects

Characteristics:

- High Strategic Priority
- High Implementation Effort
- Significant business or SEO value
- Clear dependencies or resource requirements

These opportunities should be planned as strategic projects with defined milestones, dependencies, and resource requirements.

### Tier 3 — Quick Wins

Characteristics:

- Moderate Strategic Priority
- Low Implementation Effort
- Can be implemented without major dependencies

These opportunities may be executed alongside Tier 1 work.

### Tier 4 — Planned Opportunities

Characteristics:

- Moderate Strategic Priority
- Moderate or High Implementation Effort
- Useful but not immediately critical

These opportunities should be scheduled after higher-priority initiatives.

### Tier 5 — Deferred Opportunities

Characteristics:

- Low Strategic Priority
- High Implementation Effort
- Weak business relevance
- Significant dependencies without sufficient strategic justification

These opportunities should generally be deferred.

---

## Evidence Integrity

The Skill is designed to distinguish between:

1. Observed evidence
2. Analytical inference
3. Strategic recommendation

The Skill must not fabricate:

- Search volume
- Ranking positions
- Traffic
- Conversion rates
- Revenue
- Competitor performance metrics

If evidence is insufficient, the analysis should explicitly state the limitation.

Content gaps should be treated as strategic opportunities for further validation, not guaranteed SEO wins.

---

## Analysis Output

A typical analysis may include:

1. Executive Summary
2. Website Architecture
3. Topic Clusters
4. Keyword Themes
5. Search Intent
6. Competitor Strengths
7. Competitor Weaknesses
8. Content Gaps
9. SEO Opportunities
10. Opportunity Scoring
11. Internal Linking Opportunities
12. Content Recommendations
13. 0–30 Day Roadmap
14. 31–60 Day Roadmap
15. 61–90 Day Roadmap
16. Risks and Evidence Limitations

The final roadmap should prioritize:

- Strategic value
- Business relevance
- Search intent
- Competitive gap
- Execution effort
- Dependencies
- Existing website readiness

The roadmap must not be presented as a guarantee of rankings, traffic, or revenue.

---

## Example Use Case

A user can provide a competitor website and request:

> Analyze this competitor's SEO strategy and identify the most important opportunities for my website.

The Skill should analyze observable website evidence and produce:

- Architecture findings
- Topic clusters
- Search-intent patterns
- Content gaps
- Opportunity priorities
- Internal-linking recommendations
- A practical implementation roadmap

---

## Version History

### 0.2.2

- Expanded the evaluation suite from 5 to 12 cases
- Added a structured 100-point evaluation framework
- Added explicit evaluation dimensions and an 80-point pass threshold
- Added hard-fail conditions for fabricated SEO metrics and unsupported conclusions
- Added dedicated evaluations for architecture, content strategy, search intent, content gaps, opportunity scoring, internal linking, roadmap planning, and false precision
- Formalized Strategic Priority scoring using four 1-5 dimensions
- Clarified that Implementation Effort is evaluated separately from Strategic Priority
- Added stronger anti-fabrication and evidence-integrity checks
- Expanded implementation sequencing and roadmap guidance
### 0.2.1

- Expanded the evaluation suite from 5 to 12 cases
- Added a structured 100-point evaluation framework
- Added explicit evaluation dimensions and pass threshold
- Added hard-fail conditions for fabricated SEO metrics
- Added dedicated evaluations for architecture, content strategy, search intent, content gaps, opportunity scoring, internal linking, roadmap planning, and false precision
- Formalized Strategic Priority scoring using four 1–5 dimensions
- Clarified that Implementation Effort is evaluated separately from Strategic Priority
- Added stronger anti-fabrication and evidence-integrity checks

### 0.2.0

- Added opportunity scoring reference
- Added SERP and keyword research references
- Added reusable report templates
- Added evaluation cases
- Added examples for SaaS, e-commerce, and content sites
- Added V2 script boundary documentation

### 0.1.0

- Initial SEO competitor analysis workflow

---
