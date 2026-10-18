# Ask every customer for a review automatically

After each completed job the agent drafts the same friendly review request, with your Google link, for every customer, and flags any complaint that comes back to you.

- **Agent:** Support / front-desk agent
- **Schedule:** Daily 18:00
- **Estimated time saved:** ~2 h/week (an estimate, not a measured result)
- **Works best with:** SMS / WhatsApp, Gmail / email
- **Fits:** Trades & home services, Local business owner, E-commerce / Shopify store owner, Dental / medical office, Real estate agent / team
- **Full page:** https://whatshouldmybotdo.com/use-cases/review-request-routine

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Ask every customer for a review automatically
Schedule: Daily 18:00
Tools I use: SMS / WhatsApp, Gmail / email.

Every evening, message every customer whose job/order completed today with the same short thank-you and my Google review link: [Google review link]. Send the same ask to everyone, whatever rating you expect. Don't check satisfaction first to decide who gets the link, don't ask for a positive or 5-star review, and don't offer anything in return. Optional: add one line inviting private feedback by reply; it never replaces the link. If anyone replies with a complaint, apologize briefly and alert me immediately with details.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Ask every customer for a review automatically
Run: Daily 18:00
Tools I use: SMS / WhatsApp, Gmail / email.

Instructions:
Every evening, message every customer whose job/order completed today with the same short thank-you and my Google review link: [Google review link]. Send the same ask to everyone, whatever rating you expect. Don't check satisfaction first to decide who gets the link, don't ask for a positive or 5-star review, and don't offer anything in return. Optional: add one line inviting private feedback by reply; it never replaces the link. If anyone replies with a complaint, apologize briefly and alert me immediately with details.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Ask every customer for a review automatically
Cadence: Daily 18:00
Tools I use: SMS / WhatsApp, Gmail / email.

You are my support / front-desk agent. Every evening, message every customer whose job/order completed today with the same short thank-you and my Google review link: [Google review link]. Send the same ask to everyone, whatever rating you expect. Don't check satisfaction first to decide who gets the link, don't ask for a positive or 5-star review, and don't offer anything in return. Optional: add one line inviting private feedback by reply; it never replaces the link. If anyone replies with a complaint, apologize briefly and alert me immediately with details.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Ask every customer for a review automatically
When: Daily 18:00
Tools I use: SMS / WhatsApp, Gmail / email.

1. Create a new workflow. Add a Schedule Trigger (daily).
2. Add nodes that fetch the inputs this routine needs (e.g. SMS / WhatsApp, Gmail / email).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

Every evening, message every customer whose job/order completed today with the same short thank-you and my Google review link: [Google review link]. Send the same ask to everyone, whatever rating you expect. Don't check satisfaction first to decide who gets the link, don't ask for a positive or 5-star review, and don't offer anything in return. Optional: add one line inviting private feedback by reply; it never replaces the link. If anyone replies with a complaint, apologize briefly and alert me immediately with details.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
