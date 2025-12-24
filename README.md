# Daily Tech Intelligence Aggregator & Processor (n8n)

## 🚀 Overview
This project is an AI-powered automation workflow built using **n8n** that aggregates daily technology news from multiple sources, processes the content, and delivers a curated newsletter via email.

## 🔁 Workflow Features
- Daily scheduled execution
- Fetches tech news from:
  - TechCrunch RSS
  - The Verge RSS
  - Hacker News Top Stories
  - AI-focused RSS feeds
- Merges and normalizes data
- Categorizes and summarizes news items
- Stores structured data in Google Sheets
- Sends daily newsletter via Gmail
- Tracks email delivery status

## 🧩 Workflow Diagram
![Workflow Overview](screenshots/workflow-overview.png)

## 🛠 Tools & Integrations
- n8n
- RSS Feed nodes
- HTTP Request
- OpenAI (for summarization & categorization)
- Google Sheets
- Gmail

## 📥 How to Import
1. Open n8n
2. Click **Import Workflow**
3. Select the JSON file from `workflows/`
4. Configure credentials
5. Save and activate

## ⚠️ Notes
- Credentials and API keys are **not included**
- This repository contains only workflow logic

## 👤 Author
Aravind

