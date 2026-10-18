# Win back and upsell past customers

The agent finds past customers due for a repeat job or upgrade and drafts an offer.

- **Agent:** Sales agent
- **Schedule:** 1st & 15th monthly
- **Estimated time saved:** ~3 h/week (an estimate, not a measured result)
- **Works best with:** CRM (HubSpot, GHL…), SMS / WhatsApp, Gmail / email
- **Fits:** Trades & home services, Local business owner, E-commerce / Shopify store owner, Dental / medical office, Real estate agent / team
- **Full page:** https://whatshouldmybotdo.com/use-cases/upsell-past-customers

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Win back and upsell past customers
Schedule: 1st & 15th monthly
Tools I use: CRM (HubSpot, GHL…), SMS / WhatsApp, Gmail / email.

Twice a month, find customers whose last job/order was 6–12 months ago. Draft a friendly check-in with a relevant seasonal offer. Queue for approval.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Win back and upsell past customers
Run: 1st & 15th monthly
Tools I use: CRM (HubSpot, GHL…), SMS / WhatsApp, Gmail / email.

Instructions:
Twice a month, find customers whose last job/order was 6–12 months ago. Draft a friendly check-in with a relevant seasonal offer. Queue for approval.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Win back and upsell past customers
Cadence: 1st & 15th monthly
Tools I use: CRM (HubSpot, GHL…), SMS / WhatsApp, Gmail / email.

You are my sales agent. Twice a month, find customers whose last job/order was 6–12 months ago. Draft a friendly check-in with a relevant seasonal offer. Queue for approval.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Win back and upsell past customers
When: 1st & 15th monthly
Tools I use: CRM (HubSpot, GHL…), SMS / WhatsApp, Gmail / email.

1. Create a new workflow. Add a Schedule Trigger, or the app trigger for the event (e.g. new email, new form entry, webhook).
2. Add nodes that fetch the inputs this routine needs (e.g. CRM (HubSpot, GHL…), SMS / WhatsApp, Gmail / email).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

Twice a month, find customers whose last job/order was 6–12 months ago. Draft a friendly check-in with a relevant seasonal offer. Queue for approval.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
