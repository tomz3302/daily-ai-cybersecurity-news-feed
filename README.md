# daily-ai-cybersecurity-news-feed

This workflow fetches the latest articles on AI agents, LLMs, and cybersecurity from MIT, Harvard, and top tech news sources. It filters, deduplicates, summarizes using Google Gemini, and emails a daily styled HTML digest.

## Features
- Scheduled automation
- RSS + Tavily search results
- Summarized with Gemini (LLM)
- Sends daily HTML email digest
- Focused on AI, cybersecurity, and research

## Setup
1. Clone this repo.
2. Import the workflow in your n8n instance.
3. Set credentials (Tavily, Gmail, Google Gemini) manually inside n8n.


## Security Note
This repo does not include any API keys or credentials. Make sure you define them **inside the n8n UI** or via your environment variables (never in this repo).
