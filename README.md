\# AI-Powered Social Media Content Automation



An AI-powered workflow built with n8n that automates the process of transforming article content into LinkedIn-ready posts.



\## Overview



This project demonstrates an end-to-end AI automation workflow:



Google Sheets → AI Article Summarization → AI LinkedIn Content Generation → LinkedIn Publishing



The workflow uses Google Sheets as the input trigger, Google Gemini for AI-powered summarization and content generation, and LinkedIn integration to publish the generated post.



\## Workflow



1\. Add an article URL to Google Sheets

2\. Google Sheets triggers the n8n workflow

3\. Gemini summarizes the article

4\. Gemini generates a LinkedIn-ready post

5\. The generated content is published to LinkedIn



\## Technologies Used



\- n8n

\- Google Sheets

\- Google Gemini

\- LinkedIn

\- AI / LLM workflows

\- Workflow automation



\## Key Features



\- Google Sheets-triggered automation

\- AI-powered article summarization

\- AI-generated LinkedIn content

\- Automated LinkedIn publishing

\- End-to-end workflow execution



\## Project Screenshots



\### n8n Workflow



!\[Workflow](screenshots/workflow.png)



\### Generated LinkedIn Post



!\[LinkedIn Post](screenshots/linkedin-post-1.png)



!\[LinkedIn Post](screenshots/linkedin-post-2.png)



\## Project Structure



```text

ai-social-media-content-automation/

│

├── workflow/

│   └── social-media-content-automation.json

│

├── screenshots/

│   ├── workflow.png

│   ├── linkedin-post-1.png

│   └── linkedin-post-2.png

│

└── README.md

