# linkedin-profile-discovery-engine-n8n

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=36&pause=500&color=00F5FF&center=true&vCenter=true&width=1200&lines=LinkedIn+Website+Scraper+⚡;Automation+First+Data+Pipeline;Built+with+n8n+%2B+JavaScript;From+Search+→+Structured+Data" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/n8n-Automation-red?style=for-the-badge&logo=n8n"/>
  <img src="https://img.shields.io/badge/Google-Search-blue?style=for-the-badge&logo=google"/>
  <img src="https://img.shields.io/badge/JavaScript-Logic-yellow?style=for-the-badge&logo=javascript"/>
  <img src="https://img.shields.io/badge/Google%20Sheets-Database-green?style=for-the-badge&logo=googlesheets"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=YOUR_GITHUB_USERNAME&label=PROFILE+VIEWS&color=0ef&style=flat-square"/>
</p>


Full Video demo is here :
https://drive.google.com/file/d/1CpXwc4x5KAg6S4NNe3kV8Vd90-OciMNN/view?usp=sharing

---------------------------

workflow :
<img width="1920" height="1080" alt="Screenshot 2025-12-23 082143" src="https://github.com/user-attachments/assets/6fe16e4f-bf08-4f12-8942-fb8488288b4e" />

-------------------------

Result :
<img width="1920" height="1080" alt="Screenshot 2025-12-23 082257" src="https://github.com/user-attachments/assets/a99ee671-0f80-4f1f-af55-2491fdb6fd4b" />

--------------------------

🚀 Project Summary 

An automation-first LinkedIn profile discovery and data extraction system built using n8n, Google Search, and Google Sheets.

This workflow programmatically searches LinkedIn profiles via Google, extracts structured profile metadata (URL, name, title, description), throttles requests safely, and stores clean, deduplicated results into Google Sheets — all without manual effort.

Designed as a scalable lead research engine, not a one-off scraper.

🧠 What Makes This Project Legit (not beginner)

Event-driven automation (n8n)

Rate-limit safe scraping logic

Structured data extraction

Google Sheets as a lightweight database

Reusable & extensible workflow

Real-world lead research use case

This is exactly the kind of system growth teams, recruiters, and data analysts build internally.
--------------------------

## 🧠 What This Project Actually Does

This is **not a browser scraper**.  
This is a **search-driven LinkedIn profile discovery engine**.

The workflow:
- Uses Google Search to find LinkedIn profiles
- Extracts structured profile metadata
- Applies throttling to avoid abuse
- Stores clean, usable data in Google Sheets
- Runs end-to-end without human intervention

Think of it as a **mini lead-intelligence pipeline**.

---

## ⚙️ Automation Flow (High-Level)

```text
Trigger
  ↓
Search Keywords Setup
  ↓
Google Search Request
  ↓
Profile URL Extraction
  ↓
Rate-Limit Control (Wait)
  ↓
Google Sheets Insert / Update
  ↓
JS Logic (Cleanup + Validation)
  ↓
Loop / Stop
-------------

