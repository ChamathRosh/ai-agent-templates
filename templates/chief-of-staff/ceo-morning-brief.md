# CEO morning brief in 5 minutes

One message each morning: calendar, urgent emails, money in/out, and the 3 things that move the business today.

- **Agent:** Chief of Staff / CEO agent
- **Schedule:** Daily 7:30
- **Estimated time saved:** ~3 h/week (an estimate, not a measured result)
- **Works best with:** Gmail / email, Google Calendar, Stripe
- **Fits:** every business
- **Full page:** https://whatshouldmybotdo.com/use-cases/ceo-morning-brief

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: CEO morning brief in 5 minutes
Schedule: Daily 7:30
Tools I use: Gmail / email, Google Calendar, Stripe.

Every morning, read my calendar for today, my unread emails from the last 24h and yesterday's revenue. Send me a brief: (1) meetings with one prep note each, (2) emails that need my reply with a suggested one-line answer, (3) money in/out, (4) the 3 highest-leverage tasks for today. Keep it under 200 words.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): CEO morning brief in 5 minutes
Run: Daily 7:30
Tools I use: Gmail / email, Google Calendar, Stripe.

Instructions:
Every morning, read my calendar for today, my unread emails from the last 24h and yesterday's revenue. Send me a brief: (1) meetings with one prep note each, (2) emails that need my reply with a suggested one-line answer, (3) money in/out, (4) the 3 highest-leverage tasks for today. Keep it under 200 words.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: CEO morning brief in 5 minutes
Cadence: Daily 7:30
Tools I use: Gmail / email, Google Calendar, Stripe.

You are my chief of staff / ceo agent. Every morning, read my calendar for today, my unread emails from the last 24h and yesterday's revenue. Send me a brief: (1) meetings with one prep note each, (2) emails that need my reply with a suggested one-line answer, (3) money in/out, (4) the 3 highest-leverage tasks for today. Keep it under 200 words.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: CEO morning brief in 5 minutes
When: Daily 7:30
Tools I use: Gmail / email, Google Calendar, Stripe.

1. Create a new workflow. Add a Schedule Trigger (daily).
2. Add nodes that fetch the inputs this routine needs (e.g. Gmail / email, Google Calendar, Stripe).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

Every morning, read my calendar for today, my unread emails from the last 24h and yesterday's revenue. Send me a brief: (1) meetings with one prep note each, (2) emails that need my reply with a suggested one-line answer, (3) money in/out, (4) the 3 highest-leverage tasks for today. Keep it under 200 words.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
