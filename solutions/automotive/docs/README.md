# 🚗 AI Receptionist for Car Showrooms

## Overview
Complete AI-powered receptionist solution for car dealerships and auto showrooms.

## Features
- 24/7 Vehicle Inquiry Handling
- Test Drive Scheduling
- Service Appointment Booking
- Trade-in Evaluation
- Financing Pre-qualification
- Inventory Updates
- Multi-language Support

## Architecture
```
┌─────────────────────────────────────────┐
│           AI Auto Receptionist          │
├─────────────────────────────────────────┤
│                                         │
│  Phone Call → Evolution API → AI Agent  │
│                                         │
│  WhatsApp → Evolution API → AI Agent    │
│                                         │
│  AI Agent → n8n → Inventory System      │
│                                         │
│  n8n → CRM → Lead Tracking              │
│                                         │
│  Calendar → Google Calendar → Test Drives│
│                                         │
└─────────────────────────────────────────┘
```

## Components
| Component | Technology |
|-----------|------------|
| AI Agent | OpenClaw + Kimi K2.5 |
| WhatsApp | Evolution API |
| Workflows | n8n |
| CRM | Google Sheets / Custom |
| Inventory | Integration with dealer system |
| Calendar | Google Calendar |

## Pricing
- Starter: $500/month
- Professional: $800/month
