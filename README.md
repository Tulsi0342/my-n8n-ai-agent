# Daily News AI Agent

An automated AI agent built with n8n that delivers personalized news directly to my email every morning.

## What it does

This AI agent automatically:
- Fetches the latest **tech news**
- Fetches the latest **world news**
- Sends both categories to my email at **7:00 AM** every day

## Features

- Automated daily delivery at 7 AM
- Curated tech industry updates
- Global world news summary
- Delivered straight to email inbox

## Requirements

To use this workflow, you'll need:
- n8n installed (self-hosted or n8n Cloud)
- API keys for news sources (specify which ones you use - like NewsAPI, RSS feeds, etc.)
- Email service configured in n8n (Gmail, SMTP, etc.)
- AI service API key (if using ChatGPT, Claude, etc. to summarize news)

## How to use

1. Download the workflow JSON file from this repository
2. Open n8n and go to **Workflows**
3. Click **Import from File** and select the downloaded JSON
4. Configure your credentials:
   - Add your news API key
   - Add your email credentials
   - Add your AI service API key
5. Update the email address to yours
6. Activate the workflow

## Schedule

The workflow runs automatically every day at 7:00 AM (timezone: [mention your timezone])

## Built with

- n8n workflow automation
- [Name the news API you're using]
- [Name the AI service - ChatGPT, Claude, etc.]
- Email service
