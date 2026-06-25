## AI-Powred Sales Assistant (n8n)
## Overview
This project consists of two independent n8n workflows power this AI Sales Assistant. The first captures customer inquiries through a webhook, uses a Groq-powered AI Agent to generate responses, and logs leads to Google Sheets. The second monitors Gmail replies, maintains conversation memory, and automates personalized follow-up communication.
## Features
Automated customer inquiry handling
AI-powered response generation using Groq
Conversation memory for contextual replies
Gmail integration for email communication
Google Sheets lead tracking
Automated follow-up responses
No-code/low-code implementation with n8n

## Workflow Architecture
Workflow 1: Lead Capture & Initial Response
Webhook → Set Node → AI Agent → Gmail → Google Sheets
Function:
Receives customer inquiries via webhook
Processes requests with an AI Agent using data in the Google Sheets tool
Generates personalized email responses
Logs customer information and interactions in Google Sheets

## Workflow 2: Follow-Up Automation
Gmail Trigger → AI Agent → Gmail Reply
Function:
Monitors incoming customer email replies
Maintains conversation context using memory
Generates intelligent follow-up responses
Continues the conversation automatically

## Tech Stack
n8n
Groq Chat Model
Gmail
Google Sheets
AI Agent
Simple Memory
