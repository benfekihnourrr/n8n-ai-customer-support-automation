# AI-Powered Customer Support Automation with n8n

## Overview

An AI-powered customer support workflow built using n8n, Google Gemini, Gmail, and Google Sheets.

The system automatically receives customer emails, classifies customer requests, generates professional reply drafts, and logs interactions in Google Sheets.

All replies are saved as Gmail drafts for human review before sending.

## Tech Stack

- **n8n Cloud** — Workflow orchestration
- **Google Gemini AI** — Email classification and response generation
- **Gmail API** — Incoming email detection and draft creation
- **Google Sheets** — Customer support logging

## Workflow

1. Gmail Trigger detects a new customer email.
2. Basic LLM Chain uses Gemini AI to analyze the message.
3. Gemini returns a category, priority, and suggested reply.
4. Edit Fields prepares structured data.
5. Google Sheets stores the customer interaction.
6. Gmail creates a reply draft for human review.

## Key Features

- Automated customer email processing
- AI-powered classification
- Priority identification
- Personalized reply generation
- Google Sheets integration
- Human-in-the-loop email review

## Demo

Add your screen recording link here.

## Screenshots

Add workflow and execution screenshots here.

## Setup

1. Import `workflow.json` into n8n.
2. Configure Gmail and Google Sheets credentials.
3. Configure a Google Gemini API credential.
4. Select a supported Gemini model.
5. Create a Google Sheet with the required columns.
6. Test the workflow using fictional customer emails.
7. Activate the workflow after successful testing.

## Security

Credentials are not included in the public repository. Customer information and sensitive workflow metadata must be removed before publishing.

## Future Improvements

- Automatic escalation of high-priority complaints
- Duplicate email detection
- Customer support analytics dashboard
- Knowledge-base integration for more accurate replies

## Project Status

Functional prototype — tested with sample customer emails.
