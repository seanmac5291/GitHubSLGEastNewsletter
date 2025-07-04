# GitHub Customer Newsletter

This repository contains templates and instructions for creating a monthly GitHub customer newsletter focused on updates for government agency customers.

## Purpose

The newsletter is personally curated to provide updates on:
- New GitHub product launches and features
- Metrics and best practices
- Learning resources
- Upcoming events and webinars
- Industry news relevant to government technology (see GovTech Grapevine)

It helps engagement by keeping customers informed on key developments. Many customers leverage this content by sharing resources, updates, and event links in their internal developer community portals.

## Target Audience

- **Primary**: Engineering Managers, DevOps Leads, and IT Leadership within government agencies (primarily state and local)
- **Secondary**: Developers and platform engineering teams

## Repository Structure

- `.github/prompts/` - Contains templates and instructions for generating newsletters
  - [`custom_instructions.md`](.github/prompts/custom_instructions.md) - Detailed guidelines for newsletter content and formatting
  - [`newsletter_template.md`](.github/prompts/newsletter_template.md) - Base template for monthly newsletters
- `Newsletters/` - Contains monthly newsletter issues (e.g., `June2025.md`)

## Key Newsletter Sections

1. **Copilot Updates** - Latest releases, features, and enterprise-focused content
   - Latest Releases
   - Copilot at Scale (enterprise adoption, metrics, training)
   - Improved IDE Feature Parity
2. **Webinars, Events, and Recordings** - Upcoming learning opportunities with dates and categories
   - All event times must be listed in Eastern Time (ET)
   - Virtual events use a Markdown table with columns for Date, Time (ET), Event, and Categories
   - In-person events use bullet points with embedded links
   - On-demand events are clearly labeled and linked
3. **Nicole's Notes** - "Did You Know?" format focusing on specialized Copilot features, legal/compliance aspects, or unique use cases
4. **The GovTech Grapevine** - Curated industry news with 10-15 word summaries and embedded links
5. **Optional Sections** - Security updates, DevOps integrations, GHAS, Actions, General Platform Updates, etc.

## Newsletter Style

- Professional but conversational tone
- Consistent GitHub terminology
- Clear section headers and markdown formatting
- **All links must be embedded** (no raw URLs)
- **All event times must be in Eastern Time (ET)**
- Clear labeling of feature release types (GA vs PREVIEW)
- Use bullet points for lists and tables for events as described above

## Content Selection Criteria

Content is prioritized based on:
1. Recency (focus on updates from the past month)
2. Feature maturity (GA features prioritized)
3. Relevance to government agency IT leadership
4. Information density (balance of detail and brevity)

## How to Use

Follow the formatting guidelines in [`.github/prompts/custom_instructions.md`](.github/prompts/custom_instructions.md) to ensure consistency when creating monthly newsletters. Use the provided template and refer to recent issues for examples.

## Contact

For questions about this repository or newsletter content, please reach out directly.
