# Personal learning digest

The agent reads the newsletters you never get to and sends the 5 ideas worth your time.

- **Agent:** Chief of Staff / CEO agent
- **Schedule:** Sundays 9:00
- **Estimated time saved:** ~2 h/week (an estimate, not a measured result)
- **Works best with:** Gmail / email
- **Fits:** every business
- **Full page:** https://whatshouldmybotdo.com/use-cases/learning-digest

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Personal learning digest
Schedule: Sundays 9:00
Tools I use: Gmail / email.

Every Sunday, read the newsletters in my inbox from this week, then give me the 5 most useful ideas with one action each, and archive the rest.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Personal learning digest
Run: Sundays 9:00
Tools I use: Gmail / email.

Instructions:
Every Sunday, read the newsletters in my inbox from this week, then give me the 5 most useful ideas with one action each, and archive the rest.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Personal learning digest
Cadence: Sundays 9:00
Tools I use: Gmail / email.

You are my chief of staff / ceo agent. Every Sunday, read the newsletters in my inbox from this week, then give me the 5 most useful ideas with one action each, and archive the rest.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Personal learning digest
When: Sundays 9:00
Tools I use: Gmail / email.

1. Create a new workflow. Add a Schedule Trigger, or the app trigger for the event (e.g. new email, new form entry, webhook).
2. Add nodes that fetch the inputs this routine needs (e.g. Gmail / email).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

Every Sunday, read the newsletters in my inbox from this week, then give me the 5 most useful ideas with one action each, and archive the rest.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
