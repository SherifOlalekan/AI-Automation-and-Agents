# 🤖Automation Agents Pack 1

This repository contains 5 automation agents built with **Make (Integromat)**, designed to streamline workflows for engineering, productivity, and job opportunities. Each agent demonstrates how AI and automation can effectively solve real-world problems.

---

## 📌 Agents Overview

### 1. 📰 Engineering News Aggregator
- **Goal:** Stay updated with the latest engineering and tech news.
- **Workflow:**
  - Fetches articles from **RSS feeds**.
  - Iterates through the items and aggregates them.
  - Sends a neatly formatted digest directly to **Subscribers email address**.
- **Value:** Cuts through noise and delivers only relevant news updates in one place.

---

### 2. 📋 Site Report Summarizer
- **Goal:** Automate site reporting for engineering/construction projects.
- **Workflow:**
  - Accepts site work updates (via email or input).
  - AI summarizes work done, blockers, and plans for the next day.
  - Sends the structured report via telegram in a professional format.
- **Value:** Saves time for engineers and ensures consistent, daily reporting.

---

### 3. 📂 Resume Logger
- **Goal:** Organize incoming job applications seamlessly.
- **Workflow:**
  - Monitors Gmail for new applications.
  - Extracts the resume attachment.
  - Stores the file in a structured **Google Drive** folder.
  - Send a customised acknowledgement email to the applicant.
  - Notify the recipient of a new application.
- **Value:** No more manual downloading or searching — resumes are auto-archived.

---

### 4. ✅ Task Extractor & Reminder Agent
- **Goal:** Convert tasks hidden in emails into actionable reminders.
- **Workflow:**
  - AI parses emails for tasks and deadlines.
  - Logs tasks into **Google Sheets**.
  - Adds reminders to **Google Calendar**.
  - Replies to the sender confirming the task.
  - Includes duplicate detection to prevent redundancy.
  - In a situation when the task is not well-detailed, an automatic email is sent asking the sender to provide more context to the task
- **Value:** Ensures no task slips through the cracks and adds accountability.

---

### 5. 💼 Job Opportunities Finder
- **Goal:** Curate remote/tech job postings in real-time.
- **Workflow:**
  - Fetches jobs from **Adzuna API** (filtered for remote tech jobs).
  - Limits to 5 jobs per run.
  - Aggregates title, short description, and application link.
  - Sends directly to **Telegram**.
- **Value:** Job seekers get curated, relevant roles without endless searching.

---

## 🚀 Tech Stack
- **Make (Integromat)** – Workflow automation platform  
- **Telegram Bot API** – Notifications & digests  
- **Gmail + Google Drive + Google Sheets + Google Calendar** – Productivity tools  
- **Adzuna API** – Job data  
- **Custom AI Prompts** – Summarization & extraction logic  

---

## 📎 Submission Notes
This repo documents the 5 working agents submitted for the **Wokkah AI Challenge**.  
Each blueprint/flow can be exported and reused in Make.

---

