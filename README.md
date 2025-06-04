# HR Assistant – Application Filtering & Candidate Scoring Automation
HR Assistant is an intelligent automation workflow that helps recruitment agencies automatically gather, evaluate, and score candidate applications — saving hours of manual filtering and reducing human errors.

This tool integrates with Gmail (or any CRM/email tool), extracts CV data, evaluates candidate fit using AI, and logs structured insights into Google Sheets. It’s designed to plug into your existing processes with no technical skills required from your team.

##  What It Does
📥 Automatically detects incoming job applications from email or CRM.

🧾 Extracts candidate data from CVs: experience, education, skills.

🎯 Scores candidates based on job fit using AI (Gemini/OpenRouter).

📊 Logs structured results (contact details, job title, score, notes) into Google Sheets.

🧼 Cleans inbox automatically (tag, archive, or delete processed emails).

## 💼 Who Is It For?
Recruitment agencies, especially those handling high application volumes, with a focus on:

IT roles (Backend, Frontend, DevOps, Data, QA, etc.)

Use of Gmail, ATS tools, or CRMs

Desire to integrate automation without technical hiring or retraining

No coding skills are required for your staff — the system runs in the background and feeds your dashboard.

## 🛠️ Tech Stack
🔁 n8n – Workflow automation

📧 Gmail – Email trigger & actions

📂 Google Drive – CV handling

📑 Google Sheets – Candidate data logging

🧠 Gemini / OpenRouter (ChatGPT) – CV evaluation, job-fit scoring

## 🔧 Requirements
To set it up, you’ll need:

A VPS or cloud server to host n8n

API access to Gemini, OpenRouter, or OpenAI

Access to Gmail or your CRM with webhook/email forwarding support

Basic setup time (1–2h, documented)

## 📈 Why Use It?
⏱ Save hours of manual CV reading

🔄 Automate repetitive filtering and reduce human fatigue

💡 Get scoring logic based on skills, degrees, and experience

📂 Centralized data for team collaboration

🧩 Easy to integrate with existing workflows

## 🔍 Example Output
Each candidate is evaluated and stored like:

Name	Position Applied	Score	Experience	Education	Key Skills	Fit Summary
Jane Doe	Frontend Dev	88%	4 years	MSc	React, CSS, Figma	Strong match, needs JS upgrade
John Smith	DevOps Engineer	72%	3 years	BSc	AWS, Docker, Terraform	Good match for junior roles

## 📦 Setup & Installation (Coming Soon)
A full guide will be included to help agencies or freelancers deploy and customize it within 1–2 hours.

📬 Contact
If you're an agency or freelancer looking to automate recruitment, feel free to open an issue or reach out.
