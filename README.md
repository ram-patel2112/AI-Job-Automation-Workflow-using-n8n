🚀 AI-Powered Job Application Assistant
Automated Resume Generation & Job Workflow using n8n

📌 Overview

This project is an AI-driven job application automation system built using n8n.

It allows users to interact through messaging platforms such as:

✅ WhatsApp

✅ Discord

The system automatically:

✅ Collects user details

✅ Generates ATS-friendly resumes

✅ Searches for relevant job opportunities

✅ Logs applications

✅ Sends confirmation notifications

All processes are fully automated through an event-driven workflow.

🎯 Key Features

✅ Event-driven architecture (WhatsApp & Discord triggers)

✅ AI-powered resume generation

✅ Job search integration via API

✅ Automatic PDF resume creation

✅ Google Sheets logging (user profiles & applications)

✅ Email confirmation system

✅ Multi-platform response routing

🏗 Workflow Architecture
1️⃣ User Input (Trigger Layer)

Triggers:

✅ WhatsApp Trigger

✅ Discord Bot Trigger

Users provide:

✅ Name

✅ Skills

✅ Experience

✅ Education

✅ Target Job Role

2️⃣ AI Processing Layer

The workflow uses:

✅ Groq (LLaMA 3.1 model)

✅ LangChain Agent inside n8n

Capabilities:

✅ Structured data extraction

✅ Resume content generation

✅ Job query understanding

✅ ATS-friendly formatting

3️⃣ Resume Generation Layer

✅ HTML resume template generation

✅ Automatic PDF conversion

✅ Dynamic file naming

4️⃣ Data Persistence Layer

Integrated with:

✅ Google Sheets

Used for:

✅ Storing user profiles

✅ Logging job applications

✅ Tracking submission status

5️⃣ Notification Layer

✅ Email confirmation via Gmail integration

✅ Platform-based response routing:

✅ WhatsApp reply

✅ Discord message response

🛠 Technologies Used

✅ n8n (Workflow Automation)

✅ WhatsApp API

✅ Discord Bot API

✅ Groq LLaMA 3.1

✅ LangChain Agent

✅ Google Sheets API

✅ Gmail API

✅ HTTP Request Nodes

✅ SerpAPI (Job Search Integration)

🔄 End-to-End Flow

✅ User sends job profile via WhatsApp or Discord

✅ System extracts structured data

✅ AI generates resume content

✅ Resume is converted to PDF

✅ Job search is executed

✅ Application data is logged

✅ Confirmation email is sent

✅ User receives response on the original platform

📊 System Design Highlights

✅ Event-driven automation

✅ Multi-channel input handling

✅ AI-agent orchestration

✅ Structured output parsing

✅ API-based integrations

✅ Automated document generation

⚙️ Setup Instructions

✅ Install n8n

✅ Import the provided JSON workflow file

✅ Configure the following credentials:

✅ WhatsApp API

✅ Discord Bot API

✅ Groq API

✅ Google Sheets OAuth

✅ Gmail OAuth

✅ SerpAPI

✅ Activate the workflow

🔐 Security Note

✅ Credentials and API keys are not included in this repository.

✅ You must configure your own credentials inside n8n before running the workflow.

🚀 Why This Project Matters

This project demonstrates:

✅ Real-world AI integration

✅ Backend automation logic

✅ API orchestration

✅ Resume optimization

✅ Multi-platform messaging automation

✅ Event-driven system design

It simulates a production-level AI job assistant.
