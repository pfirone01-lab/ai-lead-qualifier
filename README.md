# AI Lead Qualifier

A lightweight, browser-based tool that takes any lead description and returns five structured outputs in seconds; built for automation specialists and small business owners who need fast, consistent lead triage without a CRM or manual effort.

---

## What It Does

Paste a raw lead description; a WhatsApp message, form submission, email, or a few sentences about a prospect; and the app returns a structured qualification report covering Lead Type, Urgency, Recommended Action, a Draft Response, and a Confidence Level. It is designed for freelancers, automation consultants, and small business owners who handle leads manually and want to move faster without building a full CRM workflow.

---

## Live Demo

[Open the app here →](https://pfirone01-lab.github.io/ai-lead-qualifier/)

No sign-up required. Add your Groq API key in the settings panel and start qualifying leads immediately.

---

## Screenshots

*Screenshots coming soon.*

---

## How to Run Locally

1. Download the `firone-lead-qualifier-final.html` file from this repository
2. Get a free Groq API key at [console.groq.com/keys](https://console.groq.com/keys)
3. Open the file in any text editor (VS Code, Notepad, TextEdit)
4. Find the placeholder `YOUR_GROQ_API_KEY` and replace it with your actual key
5. Save the file and open it in your browser — no server or build step needed

---

## Tech Stack

- HTML, CSS, JavaScript (single self-contained file)
- [Groq API](https://console.groq.com) — `llama-3.3-70b-versatile` model
- GitHub Pages (hosting)
- Designed with [Claude](https://claude.ai) by Anthropic

---

## How It Works

The entire app lives in one HTML file; no frameworks, no build tools, no backend. When a user submits a lead description, the frontend sends a direct API request to Groq's inference endpoint, which runs the Llama 3.3 70B model. The system prompt was designed and refined in Claude to produce consistent, structured JSON output across five qualification fields. That response is parsed and rendered as a clean report in the browser. Everything — the UI, the prompt logic, and the API call — runs client-side.

---

## About the Builder

**Philemon Firone** is an n8n automation specialist and bot developer based in Nigeria who helps small businesses replace manual processes with reliable, scalable workflow systems. He builds using n8n, REST APIs, Claude, and messaging platforms like WhatsApp and Telegram.

[Connect on LinkedIn →](https://www.linkedin.com/in/philemon-firone-338529299/)

---

## Part of the 30-Day Course

This tool was built as the capstone project of a 30-day intensive course focused on building real-world AI and automation systems using Claude and n8n. Over 30 days, the course covered prompt engineering, workflow design, multi-step agent logic, API integration, and client-ready system delivery. The AI Lead Qualifier represents the full stack of those skills applied to a single, practical, shippable product.
