# Creator Operations

[中文](README.md) | English

An AI-assisted workspace for creator research, outreach preparation and campaign execution.

[Try the personal demo](https://ops.mccoco.xyz/) · [View the full case study](https://mccoco.xyz/portfolio)

![Redacted Creator Operations recommendation workflow](https://mccoco.xyz/portfolio/assets/projects/outreach/flow/recommendation-live.png)

## Why I built it

Creator operations often lives across spreadsheets, inboxes and individual experience. As campaign volume grows, teams lose context, repeat research and spend too much time checking what should happen next.

I translated the operating model I use in overseas creator marketing into one connected product workflow:

1. Interpret a campaign brief and retrieve relevant creators.
2. Investigate recent public content and prepare a recommendation.
3. Draft personalized outreach for human review.
4. Extract quoted rates and delivery terms from replies.
5. Surface follow-ups, blockers and the next recommended action.

## My role

I defined the operating rules, product scope and interaction model, then built and deployed the personal demonstration version across the frontend, API and workflow layers.

The work combines creator-marketing judgment with product design and implementation. The goal is not to remove human decision-making; it is to give operators better context before they decide.

## Product tour

### Creator recommendation

![Redacted creator recommendation screen](https://mccoco.xyz/portfolio/assets/projects/outreach/flow/recommendation-live.png)

Retrieves candidates from a structured creator library and organizes the evidence needed for review.

### Outreach preparation

![Redacted outreach draft screen](https://mccoco.xyz/portfolio/assets/projects/outreach/flow/draft-redacted.png)

Builds contextual drafts for operator review and supports time-zone-aware outreach planning.

### Reply interpretation

![Redacted reply interpretation screen](https://mccoco.xyz/portfolio/assets/projects/outreach/flow/reply-parse-redacted.png)

Turns unstructured replies into reviewable commercial terms and explicit next steps.

### Execution visibility

Shows where work is blocked and keeps research, communication and delivery context connected.

## System boundary

The personal demo is built around React and TypeScript, a Python API, PostgreSQL, Redis and containerized services. AI-assisted retrieval and drafting are separated from human review and approval.

This repository is intentionally a public product showcase, not the production source repository. It contains no customer records, creator contact database, email bodies, credentials, deployment configuration or proprietary workflow implementation.

## Access and feedback

- Product demo: [ops.mccoco.xyz](https://ops.mccoco.xyz/)
- Portfolio: [mccoco.xyz/portfolio](https://mccoco.xyz/portfolio)
- Feedback: use this repository's Issues tab

Copyright © 2026 Mark Shi. All rights reserved.
