# Podcast Content Generator - n8n Workflow

## 🎯 What it Does

Transforms podcast titles and URLs into structured content database entries with AI-generated SEO descriptions, metadata extraction and automated image hosting.

**Input:** Form submission with podcast title and Apple Podcast URL  
**Output:** Complete podcast database entry with AI-optimised content

## ⚡ Quick Setup

1. Import `Podcast_Content_Generator.json` into n8n
2. Configure credentials:
   - **OpenAI API** - For content generation
   - **Google Sheets** - Connect to Google account, replace `GOOGLE SHEET NAME` and `GOOGLE SHEET ID` with your spreadsheet details
   - **ImgBB API** - Replace `IMGBB API KEY` with your image hosting key
3. Customise the AI prompt for your specific use case (currently optimised for true crime podcasts)
4. Test with a sample podcast title and URL

## 🛠️ Built With

- **n8n** (workflow automation)
- **OpenAI GPT-4** (content generation)
- **Google Sheets** (database storage)
- **ImgBB** (image hosting)
