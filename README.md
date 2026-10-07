# 🔥 Autonomous AI Sales Leads Qualifier & Automation Engine

A production-ready, autonomous AI Sales Agent built in Make.com designed to instantly qualify B2B/high-ticket inbound leads from ad platforms and fast-track them to the sales team in under 3 seconds.

## 💼 The Business Challenge
Responding to a sales lead in 30 minutes instead of 5 minutes drops your conversion odds by 80%. When brands spend thousands of dollars on Facebook, TikTok, or Google Ads, every minute a hot lead goes unanswered is pure ad-spend down the drain. Furthermore, human sales teams waste hours manually sorting through low-budget tire-kickers.

## 🤖 The AI Agent Solution
This system replaces rigid, linear automation with an **Autonomous AI Agent**. Powered by **Make AI Toolkit (Simple Text Prompt)**, the AI agent dynamically evaluates the prospect's budget and challenge constraints against strict business logic and triggers the best operational tool autonomously.

### System Workflow:
1. **Instant Ingestion:** Captures inbound lead payloads via secure webhooks the millisecond an ad form is submitted.
2. **Autonomous Lead Scoring:** The AI evaluates the lead's monthly budget and level of urgency.
3. **Dynamic JSON Routing:** The AI injects its operational decision into a dynamic JSON string, which is immediately parsed to split the workflow into two distinct paths:
   - **🚀 HOT LEADS (Budget >= \$2,000 & Urgent/ASAP):** Bypasses standard queues. The AI Agent triggers the **Telegram Sales Bot** tool, delivering the prospect's full profile alongside an AI-generated personalized outreach script directly to the sales team's phone.
   - **📥 COLD LEADS (Low Budget / No Urgency):** The AI Agent triggers the **Google Sheets Database** tool to archive the data for automated nurture email campaigns, saving your sales representatives' energy for high-ticket clients.

## 📊 Architecture Blueprint & Output
*Paste your Mermaid diagram image link or upload it here*

### 📱 Live Emergency Hot Lead Alert (Telegram Output)
*Paste your Telegram hot lead notification screenshot here*

### 📊 Automated Archive Layout (Google Sheets Output)
*Paste your Google Sheets database screenshot here*

## 🛠️ Tech Stack
* Webhooks & Postman (API Ingestion & Testing Engine)
* Make AI Toolkit (Simple Text Prompt + JSON Injection)
* Native Make JSON Parser Module
* Telegram Bot API Gateway
* Google Sheets (Lead Nurturing Archive)

## 🚀 How to Deploy This Blueprint
1. Download the `sales-leads-qualifier-agent.json` file from this repository.
2. Go to your Make.com dashboard and create a new scenario.
3. Click the three dots (...) at the bottom menu and select **Import Blueprint**.
4. Upload the JSON file and remap your Webhook connections, Google Sheets document, and Telegram Bot tokens.

