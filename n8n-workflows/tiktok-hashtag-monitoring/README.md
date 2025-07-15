# TikTok Hashtag Trend Analysis - n8n Workflow

## 🎯 What it Does

Automatically scrapes TikTok posts for specified hashtags and generates comprehensive trend analysis with viral score calculations, creator performance tracking and professional email reports with actionable insights.

**Input:** Configurable hashtag list (startup, entrepreneur, productivity, etc.)  
**Output:** Multi-sheet analytics database with trend reports, creator insights and automated HTML email summaries

## ⚡ Quick Setup

1. Import `Tiktok_Hashtag_Monitoring.json` into n8n
2. Configure credentials:

- **Apify API** - Replace `YOUR_APIFY_CREDENTIALS` with your Apify TikTok scraper access
- **Google Sheets** - Replace `YOUR_GOOGLE_SHEETS_CREDENTIALS` and `YOUR_GOOGLE_SHEET_ID` with your spreadsheet details
- **Gmail** - Replace `YOUR_GMAIL_CREDENTIALS` and `YOUR_EMAIL_ADDRESS` with your notification email

3. Create Google Sheets structure:

- Import the 4 CSV templates: Posts, Hashtag Performance, Creator Performance, Daily Summary
- Update sheet IDs in workflow nodes to match your spreadsheet

4. Customize hashtags:

- Edit the hashtag array in "Scraper Settings" node for your niche
- Adjust `results per page` (default: 10 posts per hashtag)

5. Test with manual execution first

## 🛠️ Built With

- **n8n** (workflow automation)
- **Apify TikTok Scraper** (social media data collection)
- **Custom Viral Score Algorithm** (engagement analysis)
- **Google Sheets** (analytics database)
- **Gmail** (automated HTML reporting)

## 📊 Key Features

- **🔥 Viral Score Calculation** - Custom algorithm combining engagement rate, share velocity and creator influence
- **📈 Hashtag Performance Tracking** - Monitors trending hashtags with engagement metrics and top-performing posts
- **👑 Creator Analysis** - Identifies top performers, follower growth patterns and content strategies
- **⏰ Optimal Timing Insights** - Analyzes posting time patterns to identify peak engagement windows
- **📧 Professional Reports** - Automatically generates styled HTML email summaries with key insights
- **🔄 Multi-Niche Support** - Easily adaptable for any industry by updating hashtag configuration

## 📋 Data Outputs

**4 Google Sheets with comprehensive analytics:**

- **Posts** - Individual post performance with viral scores and engagement metrics
- **Hashtag Performance** - Trending hashtags with average engagement and top-performing content
- **Creator Performance** - Top creators with follower counts, verification status and best posts
- **Daily Summary** - High-level insights with top performers and optimal posting times
