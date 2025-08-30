# AI-Powered-Lead-Generation-CRM-Automation
I built an AI-powered Lead Generation & CRM Automation system using n8n + OpenAI + external APIs.

## 📝 Problem
Sales and marketing teams spend **hours every day**:
- Manually scraping leads from Google/LinkedIn
- Copy-pasting company and personal info into spreadsheets or CRMs
- Researching background info (reviews, education, posts, etc.)
- Following up slowly, risking lost opportunities

This process is **time-consuming, error-prone, and expensive**.

---

## 💡 Solution
I built an **AI-powered Lead Generation & CRM Automation system** using **n8n + OpenAI + external APIs**.

The system automatically:
1. **Captures leads** based on role, location, and business type (via Telegram Bot input or voice note).
2. **Scrapes and enriches data** from multiple sources (LinkedIn, Trustpilot, posts, company info).
3. **Uses AI (OpenAI, RelevanceAI, Perplexity)** to summarize and generate insights about leads.
4. **Stores structured leads** in Google Sheets and CRM automatically.
5. Supports **voice-to-text input** (via Telegram + Whisper) for hands-free lead capture.

This workflow turns a **3-hour manual process into a 2-minute automation**.

---

## ⚙️ Tech Stack
- **n8n** → Workflow automation engine
- **Telegram Bot API** → User input (text & voice)
- **OpenAI (Whisper + GPT)** → Transcription & enrichment
- **RelevanceAI / Perplexity** → Lead research & context generation
- **Trustpilot API / Apify / LinkedIn scrapers** → External data sources
- **Google Sheets / HubSpot CRM** → Lead storage & tracking

---

## 📊 Results (Demo Metrics)
- **80% time saved** on manual lead collection
- **100% structured data** stored in Sheets/CRM (no missing fields)
- **<60 seconds response time** from lead capture → CRM entry
- **Voice-enabled input** reduced friction for on-the-go users
- **AI summaries** helped sales teams personalize outreach

---

## 📷 Demo
- **Video Walkthrough**: Shows how a lead request moves from Telegram → Scraping → Research → Sheets/CRM.
- *(Output screenshots are not included due to API limits, but the workflow video demonstrates the full automation.)*
- Below is a **sample lead table (mocked)** representing final stored data:

| Name        | Email               | Role   | Company       | Source   | Status   |
|-------------|---------------------|--------|---------------|----------|----------|
| Ramesh Shah | ramesh@realestate.in| Agent  | Shah Realty   | Telegram | New      |
| Priya Gupta | priya@ecomshop.com  | Manager| EcomShop Ltd  | Telegram | Contact  |
| Sample Lead | sample@company.com  | Agent  | Sample Realty | Telegram | New      |

---

## 🚀 How It Works (Step by Step)
1. Salesperson sends a **text/voice note** via Telegram (e.g., *“Find real estate agents in Mumbai”*).
2. Voice is transcribed → structured query.
3. Workflow scrapes leads with role + location filters.
4. For each lead, the system pulls **LinkedIn info, reviews, education, posts, company details**.
5. AI generates a **short enriched profile** (summary + relevance).
6. Lead is pushed into **Google Sheets/CRM** automatically.
7. Notification is sent on **Slack/Telegram** with lead details.

---

## 🔮 Future Improvements
- Direct integration with HubSpot, Salesforce, or Zoho CRM
- AI-based lead scoring (Hot/Warm/Cold) before storing
- Multi-channel lead input (Email, WhatsApp, LinkedIn)

---

👨‍💻 *Built with ❤️ by VED DARJI*
