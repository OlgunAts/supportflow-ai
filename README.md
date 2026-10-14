# SupportFlow AI

SupportFlow AI is a responsive, interactive product concept for AI-assisted customer support operations. It demonstrates how a support copilot could triage requests, surface approved knowledge, and prepare editable reply drafts while keeping a human reviewer in control.

## Live prototype

This repository is designed for GitHub Pages and uses plain HTML, CSS, and JavaScript. Open `index.html` locally or serve the directory with any static file server.

## What works

- Responsive product landing page
- Interactive support inbox with five fictional conversations
- Ticket-level intent, urgency, sentiment, and summary views
- Editable sample reply drafts
- Browser-local “regenerate” and “approve” interactions
- Accessible navigation, reduced-motion support, and mobile layouts
- A clearly labeled server-side Claude integration architecture
- A measurable 90-day design-partner pilot plan
- A public pilot application workflow through GitHub Issues

## Demo and AI disclosure

This is a front-end product prototype. All people, companies, messages, metrics, analyses, and replies are fictional sample data. The demo does not call Claude or any other external AI API, does not send messages, and does not store customer data.

GitHub Pages only serves static files. A real Claude integration must run through a secure server-side backend or serverless function so API keys, access controls, audit logs, rate limits, and data-retention rules remain protected. **Never put a Claude API key in this repository or in browser-side JavaScript.**

## Production direction

A production implementation would add:

1. A secure server-side API gateway for model requests.
2. Permissioned helpdesk, CRM, and knowledge-base connectors.
3. Retrieval from approved sources with visible citations.
4. Human review gates, audit logs, and configurable retention.
5. Evaluation, monitoring, redaction, and rate limiting.

## Validation plan

The public site includes a 90-day validation roadmap. Its design-partner counts and ticket volumes are goals, not claims of existing traction. Pilot applicants can open a structured GitHub issue without sharing confidential or customer data.

## License

Copyright © 2026. All rights reserved. This repository is published as a product concept and portfolio demonstration.
