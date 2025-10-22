# Daily-Cyber-News-Flow-n8n

# 📰 Daily Tech News (n8n Workflow)

This n8n workflow automatically aggregates cybersecurity and technology news
from trusted sources and sends a daily summary email using OpenAI.

## Sources
- BleepingComputer
- CISA.gov
- The Hacker News
- Ars Technica
- TechCrunch Security

## Features
- Merges and deduplicates stories
- Filters only the last 24 hours
- Summarizes with GPT-4o
- Sends a formatted daily brief via Gmail

## Setup
1. Import `Daily Tech News.json` into n8n.
2. Connect your Gmail and OpenAI credentials.
3. Activate the workflow or run manually.
