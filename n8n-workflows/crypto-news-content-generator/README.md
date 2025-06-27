# Crypto News AI Content Generator - n8n Workflow

## 🎯 What it Does

Automatically monitors crypto news every 4 hours and transforms articles into multiple ready-to-publish content formats using AI, with intelligent categorisation and automated email reporting.

**Input:** Scheduled trigger (runs automatically)  
**Output:** Multi-format content database with executive summaries, LinkedIn posts, Twitter threads and newsletter snippets

## ⚡ Quick Setup

1. Import `Crypto_News_AI_Content_Generator.json` into n8n
2. Configure credentials:
   - **News API** - Replace `NEWS API KEY` with your NewsAPI.org key
   - **OpenAI API** - For AI content generation
   - **Google Sheets** - Replace `GOOGLE SHEET NAME` and `GOOGLE SHEET ID` with your spreadsheet details
   - **Gmail** - Replace `EMAIL ADDRESS` with your notification email
3. Update Gmail template:
   - Replace `GOOGLE SHEETS URL` with your actual Google Sheets sharing link
4. Adjust the schedule interval if needed (default: every 4 hours)
5. Test with manual execution first

## 🛠️ Built With

- **n8n** (workflow automation)
- **NewsAPI.org** (crypto news source)
- **OpenAI GPT-4** (content transformation)
- **Google Sheets** (content database)
- **Gmail** (automated reporting)
