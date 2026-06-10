# Autonomous AI Property Booking Agent (n8n Workflow)

An advanced, production-ready n8n workflow designed for luxury holiday rental property management. This system automatically intercepts incoming email inquiries, processes them via an intelligent AI Agent, cross-references database states, and drafts precise email responses.

## Key Automation Features
* **IMAP Email Trigger:** Automatically listens to and captures incoming guest and B2B agent inquiries in real-time.
* **AI Classification (Anthropic Claude 4.5 Sonnet):** Extracts unstructured email details into a structured data schema (intent, property name, guest counts, and dates).
* **Dynamic Calendar & Rules Check:** Fetches live availability via HTTP iCal integration and enforces strict seasonal minimum-stay booking logic.
* **Automated Pricing Engine:** Loops through night-by-night seasonal rates stored in Google Sheets to calculate exact totals and breakdowns.
* **Smart Response Generation:** Auto-substitutes customer tokens into multi-lingual templates and surfaces complete drafts directly to the user's dashboard.
