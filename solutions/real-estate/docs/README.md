# 🏠 AI Receptionist for Real Estate

## Overview
Complete AI-powered receptionist solution for real estate agencies.

## Features
- 24/7 Call Answering
- Property Inquiry Handling
- Appointment Scheduling
- Lead Qualification
- WhatsApp Automation
- Bilingual Support (Arabic/English)

## Architecture
```
┌─────────────────────────────────────────┐
│           AI Receptionist               │
├─────────────────────────────────────────┤
│                                         │
│  Phone Call → Evolution API → AI Agent  │
│                                         │
│  WhatsApp → Evolution API → AI Agent    │
│                                         │
│  AI Agent → n8n → Google Sheets         │
│                                         │
│  n8n → Google Calendar → Appointments   │
│                                         │
└─────────────────────────────────────────┘
```

## Components
| Component | Technology |
|-----------|------------|
| AI Agent | OpenClaw + Kimi K2.5 |
| WhatsApp | Evolution API |
| Workflows | n8n |
| Database | Google Sheets |
| Calendar | Google Calendar |
| Voice | LiveKit |

## Pricing
- Starter: $500/month
- Professional: $800/month
