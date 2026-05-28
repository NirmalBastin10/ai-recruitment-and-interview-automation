# AI Recruitment & Interview Automation System

An AI-powered recruitment automation workflow built using n8n, Groq LLMs, and Google Workspace APIs. The system automates the complete hiring pipeline from resume intake to interview scheduling.

The workflow automatically:
- Detects incoming job application emails
- Extracts and processes resumes from PDF, DOCX, and TXT formats
- Analyzes resumes against a Job Description using AI
- Generates structured candidate evaluation reports
- Calculates an overall fit score (0–10)
- Shortlists candidates scoring above 5
- Generates interview questions dynamically based on the candidate’s resume and technical profile
- Matches shortlisted candidates with the best available interviewer using Google Sheets-based availability and domain matching
- Creates Google Meet interview events automatically
- Sends email notifications with the Google Meet link to both the interviewer and candidate
- Adds candidates to a waitlist if no interviewer is currently available
- Dynamically reallocates waitlisted candidates when interview slots become available

The system also includes:
- AI-based skill-gap analysis for rejected candidates
- Automated Google Calendar scheduling
- Real-time interviewer availability tracking
- Automated email communication
- Google Drive resume storage
- Structured AI output parsing for reliable workflow automation

## Tech Stack

- n8n
- Groq LLM API
- Google Sheets API
- Google Calendar API
- Google Drive API
- Gmail API
---

## Workflow Overview
<img width="1582" height="942" alt="Screenshot 2026-05-28 at 4 22 07 PM" src="https://github.com/user-attachments/assets/26976a8e-247b-41da-9e12-27d27f863905" />
<img width="1581" height="941" alt="Screenshot 2026-05-28 at 4 22 30 PM" src="https://github.com/user-attachments/assets/9b7e4c76-760e-4f72-840c-35d6023c9414" />
<img width="1471" height="331" alt="Screenshot 2026-05-28 at 4 24 14 PM" src="https://github.com/user-attachments/assets/2b342e67-6495-4d41-bdb6-66d7d3225e5b" />
<img width="1112" height="236" alt="Screenshot 2026-05-28 at 4 23 21 PM" src="https://github.com/user-attachments/assets/867a1d68-d32f-4d52-96ca-39aae745bc7f" />
<img width="1467" height="218" alt="Screenshot 2026-05-28 at 4 45 51 PM" src="https://github.com/user-attachments/assets/e98bc3db-ae7d-4f64-b8a4-9794ccdf0ae1" />

## Candidate Email

<img width="1372" height="636" alt="Screenshot 2026-05-28 at 4 51 23 PM" src="https://github.com/user-attachments/assets/07f8c1c3-4939-4956-bd75-c74a45978dbe" />


---

## Interviewer Email

<img width="1373" height="461" alt="Screenshot 2026-05-28 at 4 52 10 PM" src="https://github.com/user-attachments/assets/c1ce4b11-15ca-43aa-a895-4368dd75e8b0" />
