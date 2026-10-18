# Qualify property leads fast, with your OK on each reply

New buyer/seller inquiries get a fast drafted reply with qualifying questions and viewing slots. You approve it with one tap before it sends. Instant replies are an optional upgrade.

- **Agent:** Sales agent
- **Schedule:** Always on
- **Estimated time saved:** ~6 h/week (an estimate, not a measured result)
- **Works best with:** SMS / WhatsApp, CRM (HubSpot, GHL…), Google Calendar
- **Fits:** Real estate agent / team
- **Full page:** https://whatshouldmybotdo.com/use-cases/realtor-lead-qualifier

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Qualify property leads fast, with your OK on each reply
Schedule: Always on
Tools I use: SMS / WhatsApp, CRM (HubSpot, GHL…), Google Calendar.

When a new property inquiry arrives, within 2 minutes draft a reply that asks budget, timeline, pre-approval and area and offers real viewing times from my calendar, and send me the draft to approve. Send it only after I approve. Score the lead hot/warm/cold in my CRM and alert me for hot ones. (Sending the first reply instantly without approval is an optional upgrade once you trust the wording.)

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Qualify property leads fast, with your OK on each reply
Run: Always on
Tools I use: SMS / WhatsApp, CRM (HubSpot, GHL…), Google Calendar.

Instructions:
When a new property inquiry arrives, within 2 minutes draft a reply that asks budget, timeline, pre-approval and area and offers real viewing times from my calendar, and send me the draft to approve. Send it only after I approve. Score the lead hot/warm/cold in my CRM and alert me for hot ones. (Sending the first reply instantly without approval is an optional upgrade once you trust the wording.)

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Qualify property leads fast, with your OK on each reply
Cadence: Always on
Tools I use: SMS / WhatsApp, CRM (HubSpot, GHL…), Google Calendar.

You are my sales agent. When a new property inquiry arrives, within 2 minutes draft a reply that asks budget, timeline, pre-approval and area and offers real viewing times from my calendar, and send me the draft to approve. Send it only after I approve. Score the lead hot/warm/cold in my CRM and alert me for hot ones. (Sending the first reply instantly without approval is an optional upgrade once you trust the wording.)

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Qualify property leads fast, with your OK on each reply
When: Always on
Tools I use: SMS / WhatsApp, CRM (HubSpot, GHL…), Google Calendar.

1. Create a new workflow. Add a Schedule Trigger, or the app trigger for the event (e.g. new email, new form entry, webhook).
2. Add nodes that fetch the inputs this routine needs (e.g. SMS / WhatsApp, CRM (HubSpot, GHL…), Google Calendar).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

When a new property inquiry arrives, within 2 minutes draft a reply that asks budget, timeline, pre-approval and area and offers real viewing times from my calendar, and send me the draft to approve. Send it only after I approve. Score the lead hot/warm/cold in my CRM and alert me for hot ones. (Sending the first reply instantly without approval is an optional upgrade once you trust the wording.)

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
