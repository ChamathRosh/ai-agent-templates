# Weekly client status updates

The agent writes each client a clear progress update from your tasks and messages.

- **Agent:** Ops & admin agent
- **Schedule:** Fridays 12:00
- **Estimated time saved:** ~3 h/week (an estimate, not a measured result)
- **Works best with:** Slack, Notion, Gmail / email
- **Fits:** Agency owner (marketing, web, AI), Consultant / coach / freelancer
- **Full page:** https://whatshouldmybotdo.com/use-cases/client-status-updates

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Weekly client status updates
Schedule: Fridays 12:00
Tools I use: Slack, Notion, Gmail / email.

Every Friday, for each active client, summarize what we did this week, results, what's next and anything I need from them. Draft as an email per client for approval.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Weekly client status updates
Run: Fridays 12:00
Tools I use: Slack, Notion, Gmail / email.

Instructions:
Every Friday, for each active client, summarize what we did this week, results, what's next and anything I need from them. Draft as an email per client for approval.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Weekly client status updates
Cadence: Fridays 12:00
Tools I use: Slack, Notion, Gmail / email.

You are my ops & admin agent. Every Friday, for each active client, summarize what we did this week, results, what's next and anything I need from them. Draft as an email per client for approval.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Weekly client status updates
When: Fridays 12:00
Tools I use: Slack, Notion, Gmail / email.

1. Create a new workflow. Add a Schedule Trigger (weekly).
2. Add nodes that fetch the inputs this routine needs (e.g. Slack, Notion, Gmail / email).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

Every Friday, for each active client, summarize what we did this week, results, what's next and anything I need from them. Draft as an email per client for approval.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
