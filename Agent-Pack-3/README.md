# 🤖 Automation Agents Pack 3

This repository showcases the third batch of 5 automation agents built with **Make (Integromat)**, combining AI, data automation, and communication tools to improve workflows in industries ranging from construction to digital marketing and personal development.

---

## 📌 Agents Overview

### 1. 🧱 Construction BOQ Agent
- **Goal:** Estimate material costs from user-provided inputs.
- **Workflow:**
  - User sends material name and quantity via **Telegram**.
  - AI parses input into structured JSON.
  - Checks **Google Sheets** for unit pricing.
  - Calculates total cost and sends it back to the user.
  - If the item is unavailable, provides a fallback link (Filta.ng).
- **Value:** Saves time in estimating material costs and reduces manual BOQ errors.
-  **Demo:** [Watch Construction BOQ Agent Demo ▶️](https://www.loom.com/share/94f424133b3f4ae4847f204ee6c85718)

---

### 2. 📈 Investico Agent
- **Goal:** Provide real-time insight on top gainers and losers across stocks, forex, and crypto.
- **Workflow:**
  - User selects a market category (Stocks, Forex, or Crypto) via **Telegram**.
  - AI retrieves and analyzes current market performance.
  - Formats and delivers summaries of top gainers and losers.
- **Value:** Delivers quick market insights and trend awareness without needing multiple dashboards.
- **Demo:** [Watch Investico Demo ▶️](https://www.loom.com/share/2479455478a64ee0bb0490275f28b944)

---

### 3. 🗣️ Travel-Aid (Voice Assistant)
- **Goal:** Deliver hands-free, AI-driven travel recommendations.
- **Workflow:**
  - User sends a voice note via **Telegram**.
  - **AssemblyAI** transcribes the message into text.
  - AI generates personalized travel tips or itineraries and formats them for chat.
- **Value:** Offers fast, conversational travel guidance with a human-like experience.
- **Demo:** [Watch Travel-Aid Demo ▶️](https://www.loom.com/share/249d23ee1e3c444a879e96ea5829cd25)
---

### 4. 💬 SocioGen Agent
- **Goal:** Help users create professional social media posts instantly.
- **Workflow:**
  - User sends casual text input (e.g., “Write a LinkedIn post about teamwork”).
  - **Make** sends it to **OpenRouter (AI model)**.
  - AI drafts a post and returns it with two inline buttons:
    - ✅ Approve & Post  
    - 🔄 Regenerate  
  - Upon approval, it auto-posts to platforms like **LinkedIn**, **Facebook**, or **Telegram**.
- **Value:** Saves time for content creators and ensures high-quality, platform-ready posts with minimal effort.
- **Demo:** [Watch SocioGen Demo ▶️](https://www.loom.com/share/6568f81fb148434e9bba7058d924d70b)
---

### 5. 🧭 Career Pivoteer
- **Goal:** Guide professionals in transitioning careers or planning upskilling paths.
- **Workflow:**
  - User interacts with the bot via **Telegram** (e.g., “Move from accounting to data science”).
  - AI analyzes and returns:
    - Career pathways  
    - Skill development roadmap (short, mid, long-term)  
    - Recommended resources and timelines  
  - Users can regenerate results or export plans to **Google Docs/Sheets**.
- **Value:** Provides actionable, personalized career roadmaps and replaces generic career advice with data-driven insights.
- **Demo:** [Watch Career Pivoteer Demo ▶️](https://www.loom.com/share/aca79820e2994badacbbbf59775aaef2)
---

## 🚀 Tech Stack
- **Make (Integromat)** – Workflow automation  
- **Telegram Bot API** – Chat interface  
- **Google Sheets / Docs** – Data storage and export  
- **AssemblyAI** – Voice transcription  
- **OpenRouter (AI Models)** – Intelligence layer  
- **Social Media APIs** – Publishing integration  

---

## 📎 Submission Notes
This repository documents the third batch of 5 automation agents submitted for the **Wokkah AI Challenge**, showcasing creative AI workflows that bridge multiple industries — from construction to marketing and career development.

---
