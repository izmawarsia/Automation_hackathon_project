
# Automated Assignment Deadline Reminder System

## Overview
This project is a time-based automation workflow built using n8n.
It monitors assignment deadlines stored in Google Sheets and automatically sends reminder emails before the deadline. It also marks assignments as late if overdue.

## Features:
.Scheduled workflow (runs every 15 minutes)
24-hour reminder email
2-hour reminder email
Late submission marking
Duplicate reminder prevention

## Tech Stack:

Google Forms

n8n

Google Sheets

Gmail 

## Repository Contents:

Automated Assignment Deadline Reminder System.json – n8n workflow file

output results – Workflow and system images

DOCUMENTATION_OF_DEADLINE_REMINDER_SYSTEM –  (Detailed documentation and system design)

## Setup Instructions:
**1. Install n8n**
Install n8n locally or use n8n Cloud.

**2. Import Workflow**
Open n8n
Click Import
Upload workflow.json

**3. Prepare Google Sheet**
Create a Google Sheet with the required columns:

Student Email

Assignment Title

Deadline

Submitted

24h Reminder Sent

2h Reminder Sent

Late Submission

**4. Connect Credentials:**
Add Google Sheets credentials in n8n
Add Gmail  credentials

**5. Activate Workflow**

Click Activate in n8n.
The system will now run automatically every 15 minutes.


## Demo Video 

This video is presenting the automated workflow of this system:








**6. Google Sheet Link**

https://docs.google.com/spreadsheets/d/1WtZa9SgHv-u0TqBtKoiN9QGSV4q0Qum7QTseqLrYIso/edit?usp=sharing
