🚀 InsightBoard

AI-powered research capture & auto-summarization

InsightBoard is a lightweight tool that lets you save any webpage with one click and automatically generates a clean AI summary. It’s built using a simple automation pipeline: Chrome Extension → Make.com → Groq API → Airtable.

⭐ What It Does

Save webpage title + URL instantly

Trigger AI summary generation using Groq LPU models

Store everything neatly inside Airtable

No backend servers — entirely automation-based

Designed for the Perplexity Comet Hackathon

🛠 Tech Stack

Chrome Extension (Manifest V3)

Make.com automation

Groq API for summarization

Airtable as a lightweight database

🧩 How It Works

Click the InsightBoard extension on any webpage

Your page info is sent through a Make.com webhook

Groq summarizes the content in a few seconds

Airtable updates automatically with Title, URL, Summary, and Timestamp

📌 Why I Built This

While researching online, I often open dozens of tabs and lose track of useful insights. I wanted a tool that saves sources instantly and summarizes them automatically — without writing a full backend or building a complex UI.

InsightBoard solves that problem with a clean, automation-first workflow.

📂 Included

The repository contains:

InsightBoard_Extension.zip

Chrome extension source files

Screenshots of Airtable + Make setup

README
