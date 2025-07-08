# Med Spa Concierge – AI Lead Responder (GPT + n8n + SMS)

AI-powered assistant that instantly responds to inbound med spa leads via SMS — answering questions, offering services, and nudging toward bookings. Built with automation-first architecture using GPT-4 and n8n.

---

## Why I built this

Med spa owners lose potential clients when inbound leads aren’t followed up with quickly. This assistant responds in seconds with warm, natural SMS replies — improving conversion rates and saving staff time.

---

## What it does

- **Inputs:**
  - Inbound SMS or contact form submission
  - Message content, phone number, and timestamp

- **Logic:**
  - Message is forwarded to GPT-4 with contextual instructions (e.g., spa services, hours, policies)
  - GPT generates a friendly, service-aligned response
  - Message is sent back via SMS using Surge (or Twilio)
  - Optional: responses are logged and tagged for lead source, conversion stage, etc.

- **Outputs:**
  - Context-aware reply sent via SMS within seconds
  - (Optional) logged conversation history or CRM handoff

---

## Demo

[Watch the 90-second walkthrough on Loom](https://www.loom.com/share/b31227562a3f4ca59094311f6d7cb25d)

---

## Tools Used

- [n8n](https://n8n.io/)
- [OpenAI GPT-4](https://platform.openai.com/)
- [Surge SMS](https://www.surgehq.ai/) *(or Twilio, Plivo, etc.)*
- [Supabase](https://supabase.com/) *(for lead logging + storage)*
- [Google Sheets (optional tracking)](https://workspace.google.com/products/sheets/)

---

## Notes

- Fully customizable to reflect spa tone, services, and lead funnel
- Can support FAQs (e.g., pricing, availability), auto-tagging, and handoff to front desk
- Architecture is modular — supports multiple spas, calendar integrations, or email fallback
- Designed to run 24/7 — ideal for solo owners and small chains who can't monitor DMs and texts around the clock
