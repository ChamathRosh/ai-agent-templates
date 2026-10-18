# Weekly CEO review & plan

Every Friday the agent compiles wins, numbers, stuck items and proposes next week's priorities.

- **Agent:** Chief of Staff / CEO agent
- **Schedule:** Fridays 16:00
- **Estimated time saved:** ~2 h/week (an estimate, not a measured result)
- **Works best with:** Notion, Google Sheets / Excel, Stripe
- **Fits:** every business
- **Full page:** https://whatshouldmybotdo.com/use-cases/weekly-ceo-review

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Weekly CEO review & plan
Schedule: Fridays 16:00
Tools I use: Notion, Google Sheets / Excel, Stripe.

Every Friday, summarize this week: revenue and key metrics vs last week, what shipped, what's stuck, and open loops. Propose the top 3 priorities for next week and one thing I should stop doing. Format as a short memo.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Weekly CEO review & plan
Run: Fridays 16:00
Tools I use: Notion, Google Sheets / Excel, Stripe.

Instructions:
Every Friday, summarize this week: revenue and key metrics vs last week, what shipped, what's stuck, and open loops. Propose the top 3 priorities for next week and one thing I should stop doing. Format as a short memo.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Weekly CEO review & plan
Cadence: Fridays 16:00
Tools I use: Notion, Google Sheets / Excel, Stripe.

You are my chief of staff / ceo agent. Every Friday, summarize this week: revenue and key metrics vs last week, what shipped, what's stuck, and open loops. Propose the top 3 priorities for next week and one thing I should stop doing. Format as a short memo.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Weekly CEO review & plan
When: Fridays 16:00
Tools I use: Notion, Google Sheets / Excel, Stripe.

1. Create a new workflow. Add a Schedule Trigger (weekly).
2. Add nodes that fetch the inputs this routine needs (e.g. Notion, Google Sheets / Excel, Stripe).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

Every Friday, summarize this week: revenue and key metrics vs last week, what shipped, what's stuck, and open loops. Propose the top 3 priorities for next week and one thing I should stop doing. Format as a short memo.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
