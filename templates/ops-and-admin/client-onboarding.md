# Client onboarding, with your OK on the welcome email

When a client pays, the agent drafts the welcome email with your intake form and kickoff booking link and sends it once you approve. Sending without review is an optional upgrade.

- **Agent:** Ops & admin agent
- **Schedule:** On new payment
- **Estimated time saved:** ~2 h/week (an estimate, not a measured result)
- **Works best with:** Stripe, Gmail / email, Google Calendar, Notion
- **Fits:** Agency owner (marketing, web, AI), Consultant / coach / freelancer
- **Full page:** https://whatshouldmybotdo.com/use-cases/client-onboarding

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Client onboarding, with your OK on the welcome email
Schedule: On new payment
Tools I use: Stripe, Gmail / email, Google Calendar, Notion.

When a new client pays, draft my welcome email with the intake form and kickoff booking link and send me the draft to approve. Send it only after I approve; if I don't answer, send nothing and remind me. Create their project page in Notion from my template. If they haven't booked in 48h, tell me and draft a short nudge for my approval. (Sending the welcome email automatically once you trust the template is an optional upgrade.)

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Client onboarding, with your OK on the welcome email
Run: On new payment
Tools I use: Stripe, Gmail / email, Google Calendar, Notion.

Instructions:
When a new client pays, draft my welcome email with the intake form and kickoff booking link and send me the draft to approve. Send it only after I approve; if I don't answer, send nothing and remind me. Create their project page in Notion from my template. If they haven't booked in 48h, tell me and draft a short nudge for my approval. (Sending the welcome email automatically once you trust the template is an optional upgrade.)

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Client onboarding, with your OK on the welcome email
Cadence: On new payment
Tools I use: Stripe, Gmail / email, Google Calendar, Notion.

You are my ops & admin agent. When a new client pays, draft my welcome email with the intake form and kickoff booking link and send me the draft to approve. Send it only after I approve; if I don't answer, send nothing and remind me. Create their project page in Notion from my template. If they haven't booked in 48h, tell me and draft a short nudge for my approval. (Sending the welcome email automatically once you trust the template is an optional upgrade.)

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Client onboarding, with your OK on the welcome email
When: On new payment
Tools I use: Stripe, Gmail / email, Google Calendar, Notion.

1. Create a new workflow. Add a Schedule Trigger, or the app trigger for the event (e.g. new email, new form entry, webhook).
2. Add nodes that fetch the inputs this routine needs (e.g. Stripe, Gmail / email, Google Calendar).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

When a new client pays, draft my welcome email with the intake form and kickoff booking link and send me the draft to approve. Send it only after I approve; if I don't answer, send nothing and remind me. Create their project page in Notion from my template. If they haven't booked in 48h, tell me and draft a short nudge for my approval. (Sending the welcome email automatically once you trust the template is an optional upgrade.)

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
