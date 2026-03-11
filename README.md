# ai-voice-receptionist
# AI Voice Receptionist 🤖📞

An Agentic AI system that acts as a voice receptionist capable of autonomously managing appointments.

The system integrates AI agents with automation workflows and CRM tools to perform real-world receptionist tasks such as booking, updating, and canceling appointments.

---

## Features

• Voice-based appointment booking
• CRM client lookup and creation
• Calendar availability checking
• Appointment scheduling and cancellation
• Automatic call logging

---

## Architecture

Voice User
↓
Vapi Voice AI
↓
Agent Controller (MCP Server)
↓
AI Tools

• Client Lookup
• Check Availability
• Book Appointment
• Update Appointment
• Delete Appointment

↓

Google Calendar + Google Sheets CRM

---

## Tech Stack

AI Agents
• Vapi
• MCP Server

Automation
• n8n Workflows

Integrations
• Google Calendar API
• Google Sheets CRM

---

## Repository Structure

```
agent/       → AI agent orchestration (MCP server)
workflows/   → n8n workflows for booking & CRM
analytics/   → call logging webhook
```

---

## Future Improvements

• SMS confirmations
• Payment integration
• Multi-location booking
• Dashboard analytics
