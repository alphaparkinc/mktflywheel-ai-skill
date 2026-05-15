---
name: mktflywheel-ai-skill
description: "GenPark skill: Automate AI marketing strategy and execution using the MktFlywheel framework (1 AI CMO, 4 Specialists, continuous execution)."
---

# MktFlywheel AI Skill

This skill distills the capabilities of [MktFlywheel.ai](https://www.mktflywheel.ai/) into a modular agent architecture for the GenPark ecosystem. It provides a self-driving marketing engine that orchestrates a "Shadow CMO" and a team of specialized marketing execution agents.

## Core Capabilities

- **URL-to-Strategy Generation**: Automatically scan a company URL to build a comprehensive marketing strategy tailored to specific niches.
- **Continuous Execution**: Operates a 24/7 team consisting of 1 CMO (Strategy) and 4 Specialists (Content, SEO/GEO, Engagement, Review Ops).
- **Daily Review Loop**: Aggregates all marketing actions into a concise daily briefing via Slack for quick human-in-the-loop (HITL) approval.
- **Tone Matching**: Automatically aligns all emails, posts, and articles with the target brand's voice and style.

## Niche Playbooks

The AI CMO automatically deploys specialized growth plays based on the user's vertical:

- **Micro-SaaS & Dev Tools**: Hacker News optimized plays (Show HN + working demos).
- **AI Tools & AI Apps**: Generative Engine Optimization (GEO) over traditional SEO.
- **Shopify Apps & Chrome Extensions**: Review velocity and review operations management.
- **Productized Services**: High-engagement LinkedIn comment strategies.
- **Productivity SaaS**: Asset-led growth (e.g., Notion template distribution).
- **Cross-Border Ecommerce**: Peak season timeline-driven content generation.

## Agent Roles

1. **AI CMO (The Navigator)**: Scans the product and niche, iterates the strategy weekly, posts last night's wins, and outlines the daily plan.
2. **Content Specialist**: Drafts and publishes targeted content based on the approved strategy.
3. **SEO/GEO Specialist**: Optimizes for search engines and AI generative engines.
4. **Community Engagement Specialist**: Manages outreach, comments, and community presence.
5. **Review Ops Specialist**: Monitors and drives positive reviews on key platforms (e.g., Shopify App Store, Chrome Web Store).

## Implementation Workflow

1. **Initialize**: Provide a single company URL.
2. **Scan & Plan**: The AI CMO performs the first scan (takes minutes) and assembles the plan and first drafts.
3. **Execute**: The 4 Specialists write, optimize, and publish campaigns.
4. **Review**: Operator checks the daily briefing, approves high-impact work, and adjusts goals.
