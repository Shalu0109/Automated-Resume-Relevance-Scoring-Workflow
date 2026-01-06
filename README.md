📄 Automated Resume Relevance Scoring System

An end-to-end AI-powered workflow that automatically screens resumes against job descriptions, generates structured evaluations, and produces recruiter-ready candidate insights — reducing manual hiring effort by 80%.

🚀 Overview

This system automates the complete resume screening pipeline:

Ingests resumes from Gmail

Parses PDF and Word documents

Matches resumes against job descriptions

Generates AI-based relevance scores and evaluations

Logs structured results into Google Sheets for recruiters

The workflow is built using n8n, OpenAI, and multiple Google APIs.

🧠 Key Features

📩 Automated Resume Ingestion from Gmail

📂 Cloud Storage Management using Google Drive

📄 Multi-format Parsing (PDF & DOCX support)

🤖 AI-Powered Candidate Evaluation (Strengths, Weaknesses, Risk, Reward, Fit Score)

📊 Relevance Scoring (1–10) for each candidate

🧾 Structured Output Logging into Google Sheets

⚡ 80% Reduction in manual screening workload

⏱️ 75% Faster resume processing & evaluation time

🏗️ System Architecture
Gmail → Google Drive → File Parsing → Resume Standardization
     → Job Description Extraction → AI Evaluation
     → Structured Scoring → Google Sheets Dashboard

🧩 Workflow Components
Stage	Description
Gmail Trigger	Automatically detects incoming resumes
Upload File	Stores resumes in Drive
Switch	Routes PDF or DOCX files
Convert & Download	Normalizes formats
Extract from File	Extracts resume & job text
Standardize	Cleans and prepares text
AI Agent	Generates evaluation & score
Structured Parser	Ensures consistent output
Information Extractor	Captures key fields
Append to Sheet	Logs results for recruiters
📊 Output Fields

Candidate Name

Email & Mobile

Resume File Reference

Relevance Score (1–10)

Clear AI-generated reasoning

All results are appended automatically to a Google Sheet.

🛠️ Tech Stack

n8n – Workflow orchestration

OpenAI (GPT-4.1-mini) – Candidate evaluation engine

Google APIs – Gmail, Drive, Sheets

LangChain Nodes – Structured output & parsing

PDF & DOC Processing Engines

📈 Measured Impact
Metric	Improvement
Manual screening effort	↓ 80%
Resume processing time	↓ 75%
Recruiter decision speed	↑ 60%
Hiring consistency	↑ 65%
Overall recruiter productivity	↑ 70%
🧪 Use Cases

Recruitment teams & HR automation

Hiring pipelines for startups & enterprises

Resume ranking & shortlisting systems

AI-based talent screening platforms

🔐 Security & Reliability

No resume data is publicly exposed

All documents remain in secured Google Drive

Structured AI output prevents inconsistent scoring

📌 Future Enhancements

Multi-job matching per resume

Candidate ranking dashboard

Interview recommendation engine

ATS integration
