# LeadFlow AI 2.0 — Intelligent Lead Qualification & CRM Automation

## Overview
LeadFlow AI is an AI-powered sales automation workflow built with n8n.
It automates lead validation, duplicate detection, AI-powered lead analysis,
lead scoring, CRM integration, and sales approval.

## Key Features
- Lead data validation
- Duplicate lead detection
- AI-powered lead analysis using OpenAI
- Automated lead scoring and prioritization
- Zoho CRM integration
- Gmail notifications
- AI-generated personalized sales emails
- Human approval before sending sales emails
- Error classification and email alerts through a supporting workflow

## Technology Stack
- n8n — Workflow automation
- OpenAI — AI-powered lead analysis
- Zoho CRM — Lead management
- Gmail — Notifications and approval emails
- Webhooks — Workflow triggering and approval callbacks

## Workflow
1. Receive lead information through a webhook.
2. Validate and normalize the submitted data.
3. Check for duplicate leads.
4. Analyze the lead using AI.
5. Calculate a lead score and priority.
6. Create the lead in Zoho CRM.
7. Generate a personalized sales email.
8. Request human approval before sending the email.
9. Send an error alert when a workflow failure occurs.

## Project Status
Core workflow built and tested. Preparing for secure publication,
deployment, and portfolio documentation.

## Security
This repository does not include API keys, passwords, access tokens,
private customer information, or exported credentials.
