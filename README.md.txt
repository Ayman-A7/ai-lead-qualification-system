# AI Lead Qualification System

An AI-powered lead qualification workflow built with **n8n**, **Google Gemini**, **Airtable**, **Gmail**, and **Slack**.

## Features

- 🤖 AI lead scoring using Google Gemini
- 📋 Automatic lead qualification
- 🔍 Duplicate lead detection
- 🗄️ Airtable CRM integration
- 📧 Automatic confirmation email
- 💬 Slack notifications for high-priority leads
- 🔄 Automatic record creation and updates

## Workflow

1. Customer submits a lead form.
2. AI analyzes the lead.
3. AI generates:
   - Lead Score
   - Priority
   - Recommended Service
   - Summary
4. Search Airtable for duplicate leads.
5. Update existing record or create a new one.
6. Send a confirmation email to the customer.
7. Notify the sales team in Slack if the lead is high priority.

## Tech Stack

- n8n
- Google Gemini
- Airtable
- Gmail
- Slack

## Business Value

This automation helps businesses:

- Save time on manual lead qualification
- Prioritize high-value prospects
- Prevent duplicate CRM records
- Improve response times
- Keep sales teams informed automatically

## Project Structure

```text
workflow/
screenshots/
docs/
README.md
```

## Import

Import the workflow JSON into n8n and connect your own credentials for:

- Google Gemini
- Airtable
- Gmail
- Slack

## License

MIT