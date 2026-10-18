# Daily X posts from your real work

The agent drafts daily posts from what you actually did (commits, wins, calls) so you post consistently.

- **Agent:** Content agent
- **Schedule:** Daily 8:00
- **Estimated time saved:** ~4 h/week (an estimate, not a measured result)
- **Works best with:** X / Twitter, GitHub, Notion
- **Fits:** Solo founder, Indie app developer / studio, Creator / influencer, Agency owner (marketing, web, AI)
- **Full page:** https://whatshouldmybotdo.com/use-cases/x-content-calendar

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Daily X posts from your real work
Schedule: Daily 8:00
Tools I use: X / Twitter, GitHub, Notion.

Every morning, look at what I did yesterday (commits, notes, calls, wins) and draft 3 X posts: one build-in-public update, one lesson, one useful tip. Match my tone from my best posts. Send for approval.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Daily X posts from your real work
Run: Daily 8:00
Tools I use: X / Twitter, GitHub, Notion.

Instructions:
Every morning, look at what I did yesterday (commits, notes, calls, wins) and draft 3 X posts: one build-in-public update, one lesson, one useful tip. Match my tone from my best posts. Send for approval.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Daily X posts from your real work
Cadence: Daily 8:00
Tools I use: X / Twitter, GitHub, Notion.

You are my content agent. Every morning, look at what I did yesterday (commits, notes, calls, wins) and draft 3 X posts: one build-in-public update, one lesson, one useful tip. Match my tone from my best posts. Send for approval.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Daily X posts from your real work
When: Daily 8:00
Tools I use: X / Twitter, GitHub, Notion.

1. Create a new workflow. Add a Schedule Trigger (daily).
2. Add nodes that fetch the inputs this routine needs (e.g. X / Twitter, GitHub, Notion).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

Every morning, look at what I did yesterday (commits, notes, calls, wins) and draft 3 X posts: one build-in-public update, one lesson, one useful tip. Match my tone from my best posts. Send for approval.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
