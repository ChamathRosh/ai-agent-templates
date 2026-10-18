# Weekly competitor watch

The agent tracks competitors' pricing, launches and posts and tells you what matters.

- **Agent:** Chief of Staff / CEO agent
- **Schedule:** Mondays 9:00
- **Estimated time saved:** ~2 h/week (an estimate, not a measured result)
- **Works best with:** X / Twitter
- **Fits:** Solo founder, E-commerce / Shopify store owner, Indie app developer / studio, Agency owner (marketing, web, AI)
- **Full page:** https://whatshouldmybotdo.com/use-cases/competitor-watch

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Weekly competitor watch
Schedule: Mondays 9:00
Tools I use: X / Twitter.

Every Monday, check [competitors]' websites, pricing, X posts and launches from last week. Tell me what changed and one thing I should respond to.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Weekly competitor watch
Run: Mondays 9:00
Tools I use: X / Twitter.

Instructions:
Every Monday, check [competitors]' websites, pricing, X posts and launches from last week. Tell me what changed and one thing I should respond to.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Weekly competitor watch
Cadence: Mondays 9:00
Tools I use: X / Twitter.

You are my chief of staff / ceo agent. Every Monday, check [competitors]' websites, pricing, X posts and launches from last week. Tell me what changed and one thing I should respond to.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Weekly competitor watch
When: Mondays 9:00
Tools I use: X / Twitter.

1. Create a new workflow. Add a Schedule Trigger (weekly).
2. Add nodes that fetch the inputs this routine needs (e.g. X / Twitter).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

Every Monday, check [competitors]' websites, pricing, X posts and launches from last week. Tell me what changed and one thing I should respond to.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
