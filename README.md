Overview

TalentLens AI is an intelligent recruitment automation workflow built using n8n and Google Gemini AI. The system analyzes resumes, calculates ATS scores, identifies strengths and weaknesses, recommends internship roles, generates interview questions, and automates recruiter communication.

Features
Resume Analysis
Extract text from uploaded PDF resumes
Analyze technical skills and projects
Evaluate resume structure and formatting
Generate ATS score (0–100)
Candidate Evaluation
Strength analysis
Weakness detection
Personalized improvement suggestions
Candidate summary generation
Career Guidance
Skill Gap Analysis
Learning Roadmap Generation
Internship Role Recommendations
GitHub Profile Evaluation
LinkedIn Profile Evaluation
Interview Preparation
AI-generated interview questions
Technical questions
Project-based questions
Behavioral questions
Recruitment Automation
Automatic Shortlisting
Automatic Rejection Handling
HR Notification Emails
Candidate Notification Emails
Google Sheets Candidate Database

WWorkflow Architecture

Form Submission
       │
       ▼
Resume Upload
       │
       ▼
PDF Text Extraction
       │
       ▼
Google Gemini Analysis
       │
       ▼
ATS Score Calculation
       │
       ▼
IF Condition
 ┌─────────────┐
 │ ATS ≥ 80    │
 └─────────────┘
       │
   Shortlisted
       │
       ▼
 HR Email + Student Email

 ┌─────────────┐
 │ ATS < 80    │
 └─────────────┘
       │
    Rejected
       │
       ▼
 Improvement Email + Database Entry

 Tech Stack:-
 
n8n
Google Gemini AI
Gmail API
Google Sheets
JSON Structured Output Parser

Output Generated
ATS Score
Candidate Status
Strengths
Weaknesses
Suggestions
Skill Gap Analysis
Learning Roadmap
Interview Questions
Recommended Internship Roles
GitHub Score
LinkedIn Score
Profile Feedback

Future Enhancements
Resume Version Comparison
HR Dashboard
Candidate Ranking System
Multi-Resume Bulk Screening
AI Mock Interview Module
Resume Builder
Job Recommendation Engine

Author
Buddepu Venkata Jaswanth
Full Stack Developer | AI Automation Enthusiast | n8n Workflow Builder
