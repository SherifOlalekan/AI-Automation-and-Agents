# 🤖 Automation Agents Pack 2

This repository contains another set of 5 automation agents built with **Make (Integromat)**, focused on improving safety, compliance, and operational efficiency within construction and manufacturing workflows.

---

## 📌 Agents Overview

### 1. 📦 Material Shortage Alert
- **Goal:** Automatically monitor inventory and trigger reordering.
- **Workflow:**
  - Continuously loops through inventory data in **Google Sheets**.
  - Compares current stock levels with reorder thresholds.
  - Sends automated **quote requests** to suppliers and **alerts** storekeepers via Telegram.
- **Value:** Prevents project delays and ensures timely restocking with minimal human oversight.

---

### 2. 🧾 Inspection Checklister
- **Goal:** Generate phase-specific inspection checklists without duplication.
- **Workflow:**
  - Reads project type and stage data from **Google Sheets**.
  - Creates a tailored **Google Doc** inspection checklist.
  - Verifies that no duplicate exists before generating.
  - Logs the new document link back to the master sheet.
- **Value:** Streamlines inspection compliance, standardizes checklists, and saves administrative time.

---

### 3. 📑 Quotation Logger
- **Goal:** Automatically process supplier quotations for review.
- **Workflow:**
  - Detects attached **PDF or Excel** quotation documents from emails.
  - Extracts key details — item name, quantity, and price.
  - Logs data into **Google Sheets**.
  - Notifies the procurement team instantly via **Telegram**.
- **Value:** Eliminates manual data entry, accelerates procurement, and reduces human errors.

---

### 4. 🦺 Safety Violation Detector
- **Goal:** Identify potential safety hazards from site photos.
- **Workflow:**
  - Images are uploaded via a **Google Site** form.
  - AI model analyzes for violations (e.g., missing PPE, unsafe posture).
  - Generates and sends a **violation report** to the HSE manager through Telegram.
- **Value:** Enables proactive risk detection, continuous monitoring, and improved site safety culture.

---

### 5. 🧯 Safety Tips Bot
- **Goal:** Deliver on-demand safety education via Telegram.
- **Workflow:**
  - Users select a safety topic (e.g., Fire Safety, PPE, Electrical Hazards).
  - Bot fetches relevant micro-learning tips from a **safety database**.
  - Presents it conversationally on Telegram.
- **Value:** Encourages continuous safety learning and awareness among field workers.

---

## 🚀 Tech Stack
- **Make (Integromat)** – Automation platform  
- **Telegram Bot API** – Notifications & micro-learning delivery  
- **Google Sheets + Google Docs + Gmail** – Data and document management  
- **OpenRouter (AI Models)** – Vision and text analysis  
- **Custom AI Prompts** – Safety and workflow logic  

---

## 📎 Submission Notes
This pack documents the second batch of 5 working agents submitted for the **Wokkah AI Challenge**, showcasing automation use cases across construction and manufacturing safety workflows.

---
