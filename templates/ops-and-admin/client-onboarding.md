# Client onboarding on autopilot

When a client pays, the agent sends the welcome pack, intake form and kickoff booking link.

- **Agent:** Ops & admin agent
- **Schedule:** On new payment
- **Estimated time saved:** ~2 h/week (an estimate, not a measured result)
- **Works best with:** Stripe, Gmail / email, Google Calendar, Notion
- **Fits:** Agency owner (marketing, web, AI), Consultant / coach / freelancer
- **Full page:** https://whatshouldmybotdo.com/use-cases/client-onboarding

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Client onboarding on autopilot
Schedule: On new payment
Tools I use: Stripe, Gmail / email, Google Calendar, Notion.

When a new client pays, send my welcome email with intake form and kickoff booking link, create their project page in Notion from my template, and remind me if they haven't booked in 48h.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Client onboarding on autopilot
Run: On new payment
Tools I use: Stripe, Gmail / email, Google Calendar, Notion.

Instructions:
When a new client pays, send my welcome email with intake form and kickoff booking link, create their project page in Notion from my template, and remind me if they haven't booked in 48h.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Client onboarding on autopilot
Cadence: On new payment
Tools I use: Stripe, Gmail / email, Google Calendar, Notion.

You are my ops & admin agent. When a new client pays, send my welcome email with intake form and kickoff booking link, create their project page in Notion from my template, and remind me if they haven't booked in 48h.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Client onboarding on autopilot
When: On new payment
Tools I use: Stripe, Gmail / email, Google Calendar, Notion.

1. Create a new workflow. Add a Schedule Trigger, or the app trigger for the event (e.g. new email, new form entry, webhook).
2. Add nodes that fetch the inputs this routine needs (e.g. Stripe, Gmail / email, Google Calendar).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

When a new client pays, send my welcome email with intake form and kickoff booking link, create their project page in Notion from my template, and remind me if they haven't booked in 48h.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
