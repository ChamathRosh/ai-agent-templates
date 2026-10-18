# Appointment reminders that cut no-shows

The agent confirms appointments the day before and handles reschedules.

- **Agent:** Support / front-desk agent
- **Schedule:** Daily 17:00
- **Estimated time saved:** ~3 h/week (an estimate, not a measured result)
- **Works best with:** Google Calendar, SMS / WhatsApp
- **Fits:** Local business owner, Consultant / coach / freelancer, Trades & home services, Real estate agent / team, Dental / medical office
- **Full page:** https://whatshouldmybotdo.com/use-cases/appointment-reminders

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Appointment reminders that cut no-shows
Schedule: Daily 17:00
Tools I use: Google Calendar, SMS / WhatsApp.

Every afternoon, message tomorrow's appointments to confirm. If they need to reschedule, offer 2 open slots and update the calendar. Send me the final list.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Appointment reminders that cut no-shows
Run: Daily 17:00
Tools I use: Google Calendar, SMS / WhatsApp.

Instructions:
Every afternoon, message tomorrow's appointments to confirm. If they need to reschedule, offer 2 open slots and update the calendar. Send me the final list.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Appointment reminders that cut no-shows
Cadence: Daily 17:00
Tools I use: Google Calendar, SMS / WhatsApp.

You are my support / front-desk agent. Every afternoon, message tomorrow's appointments to confirm. If they need to reschedule, offer 2 open slots and update the calendar. Send me the final list.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Appointment reminders that cut no-shows
When: Daily 17:00
Tools I use: Google Calendar, SMS / WhatsApp.

1. Create a new workflow. Add a Schedule Trigger (daily).
2. Add nodes that fetch the inputs this routine needs (e.g. Google Calendar, SMS / WhatsApp).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

Every afternoon, message tomorrow's appointments to confirm. If they need to reschedule, offer 2 open slots and update the calendar. Send me the final list.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
