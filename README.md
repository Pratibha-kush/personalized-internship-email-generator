# personalized-internship-email-generator

Overview

An AI-powered automation workflow that generates and sends personalized internship application emails automatically.

Features
Reads internship opportunities from Google Sheets
Filters pending applications
Generates personalized emails using Groq LLM
Sends emails through Gmail
Updates application status automatically
End-to-end workflow automation using n8n

Workflow
Google Sheets
      ↓
Filter Pending Applications
      ↓
Groq AI Email Generation
      ↓
Google Drive Resume Attachment
      ↓
Gmail Send
      ↓
Update Status in Google Sheets
Tech Stack
n8n
Groq API
Gmail API
Google Sheets API
Docker
Ubuntu Server
DuckDNS
Results
Automated internship outreach process
Reduced manual email drafting effort
Centralized tracking through Google Sheets
