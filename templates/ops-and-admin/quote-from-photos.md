# Quotes from customer photos

Customers text photos; the agent drafts a quote range from your price list for you to confirm.

- **Agent:** Ops & admin agent
- **Schedule:** On new photo request
- **Estimated time saved:** ~4 h/week (an estimate, not a measured result)
- **Works best with:** SMS / WhatsApp, Job management (Jobber, Housecall Pro, ServiceTitan)
- **Fits:** Trades & home services
- **Full page:** https://whatshouldmybotdo.com/use-cases/quote-from-photos

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Quotes from customer photos
Schedule: On new photo request
Tools I use: SMS / WhatsApp, Job management (Jobber, Housecall Pro, ServiceTitan).

When a customer sends photos of a job, describe the likely work, match it to my price list and draft a quote range with what's included. Send it to me to approve before the customer sees it.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Quotes from customer photos
Run: On new photo request
Tools I use: SMS / WhatsApp, Job management (Jobber, Housecall Pro, ServiceTitan).

Instructions:
When a customer sends photos of a job, describe the likely work, match it to my price list and draft a quote range with what's included. Send it to me to approve before the customer sees it.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Quotes from customer photos
Cadence: On new photo request
Tools I use: SMS / WhatsApp, Job management (Jobber, Housecall Pro, ServiceTitan).

You are my ops & admin agent. When a customer sends photos of a job, describe the likely work, match it to my price list and draft a quote range with what's included. Send it to me to approve before the customer sees it.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Quotes from customer photos
When: On new photo request
Tools I use: SMS / WhatsApp, Job management (Jobber, Housecall Pro, ServiceTitan).

1. Create a new workflow. Add a Schedule Trigger, or the app trigger for the event (e.g. new email, new form entry, webhook).
2. Add nodes that fetch the inputs this routine needs (e.g. SMS / WhatsApp, Job management (Jobber, Housecall Pro, ServiceTitan)).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

When a customer sends photos of a job, describe the likely work, match it to my price list and draft a quote range with what's included. Send it to me to approve before the customer sees it.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
