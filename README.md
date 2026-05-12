# n8n-AI-Scheduling-Workflow
AI powered appointment workflow using n8n + Google Calendar automation + OpenAI
# SchedulAI

AI-powered appointment scheduling workflow built using n8n, OpenAI, and Google Calendar.

This workflow automates:
- Appointment booking
- Availability checking
- Appointment rescheduling
- Appointment cancellations
- AI-powered conversational responses

The assistant uses an AI agent connected to Google Calendar tools to manage scheduling requests dynamically.

---

# Features

- AI scheduling assistant powered by OpenAI
- Google Calendar integration
- Automatic availability checking before booking
- Safe appointment rescheduling flow
- Cancellation handling with appointment lookup
- Webhook-based API architecture
- Built with n8n automation workflows
- Timezone-aware scheduling support
- Event ID validation for secure updates/deletions

---

# Tech Stack

- n8n
- OpenAI API
- Google Calendar API
- Webhooks
- AI Agent Workflows

---

# Workflow Capabilities

## Booking
Checks calendar availability before creating an appointment.

## Rescheduling
Finds existing appointments and safely updates them to a new available slot.

## Cancellation
Retrieves appointment details and removes events securely.

## Availability Checks
Returns open or occupied time slots and suggests alternatives when needed.

---

# Example Use Cases

- Salon appointment systems
- Clinic scheduling automation
- AI receptionist systems
- Voice-agent integrations
- Customer support automation
- Service business booking systems

---

# Setup

## Requirements

- n8n instance
- OpenAI API access
- Google Calendar integration
- Configured webhook endpoint

---

# Import Workflow

1. Clone this repository
2. Open n8n
3. Import the workflow JSON file
4. Reconnect credentials
5. Configure your webhook endpoint
6. Activate the workflow

---

# Security Notes

Sensitive credentials and identifiers have been removed from this public version:
- API keys
- OAuth credentials
- Webhook identifiers
- Calendar IDs
- Instance metadata

Reconnect your own credentials before deployment.

---

# Future Improvements

- SMS confirmations
- Email reminders
- Multi-calendar support
- Buffer time support
- Admin dashboard
- CRM integration
- Human escalation fallback
- Multi-language support

---

# License

MIT License
