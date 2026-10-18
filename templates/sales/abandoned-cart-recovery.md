# Personal abandoned-cart follow-ups

The agent writes a personal note to shoppers who left items in cart.

- **Agent:** Sales agent
- **Schedule:** Daily 19:00
- **Estimated time saved:** ~2 h/week (an estimate, not a measured result)
- **Works best with:** Shopify, Gmail / email
- **Fits:** E-commerce / Shopify store owner
- **Full page:** https://whatshouldmybotdo.com/use-cases/abandoned-cart-recovery

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Personal abandoned-cart follow-ups
Schedule: Daily 19:00
Tools I use: Shopify, Gmail / email.

Every evening, find carts abandoned in the last 24h. Draft a short personal email answering likely objections for those products and offering help. Queue for approval.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Personal abandoned-cart follow-ups
Run: Daily 19:00
Tools I use: Shopify, Gmail / email.

Instructions:
Every evening, find carts abandoned in the last 24h. Draft a short personal email answering likely objections for those products and offering help. Queue for approval.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Personal abandoned-cart follow-ups
Cadence: Daily 19:00
Tools I use: Shopify, Gmail / email.

You are my sales agent. Every evening, find carts abandoned in the last 24h. Draft a short personal email answering likely objections for those products and offering help. Queue for approval.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Personal abandoned-cart follow-ups
When: Daily 19:00
Tools I use: Shopify, Gmail / email.

1. Create a new workflow. Add a Schedule Trigger (daily).
2. Add nodes that fetch the inputs this routine needs (e.g. Shopify, Gmail / email).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

Every evening, find carts abandoned in the last 24h. Draft a short personal email answering likely objections for those products and offering help. Queue for approval.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
