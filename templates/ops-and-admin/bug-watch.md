# Bug watch from user reports

The agent scans support emails, reviews and mentions for bugs and files clean issues.

- **Agent:** Ops & admin agent
- **Schedule:** Daily 12:00
- **Estimated time saved:** ~3 h/week (an estimate, not a measured result)
- **Works best with:** GitHub, Gmail / email, X / Twitter
- **Fits:** Indie app developer / studio, Solo founder
- **Full page:** https://whatshouldmybotdo.com/use-cases/bug-watch

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Bug watch from user reports
Schedule: Daily 12:00
Tools I use: GitHub, Gmail / email, X / Twitter.

Every day, scan support emails, reviews and X mentions for bug reports. De-duplicate, write clear repro steps and draft GitHub issues labeled by severity for my review.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Bug watch from user reports
Run: Daily 12:00
Tools I use: GitHub, Gmail / email, X / Twitter.

Instructions:
Every day, scan support emails, reviews and X mentions for bug reports. De-duplicate, write clear repro steps and draft GitHub issues labeled by severity for my review.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Bug watch from user reports
Cadence: Daily 12:00
Tools I use: GitHub, Gmail / email, X / Twitter.

You are my ops & admin agent. Every day, scan support emails, reviews and X mentions for bug reports. De-duplicate, write clear repro steps and draft GitHub issues labeled by severity for my review.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Bug watch from user reports
When: Daily 12:00
Tools I use: GitHub, Gmail / email, X / Twitter.

1. Create a new workflow. Add a Schedule Trigger (daily).
2. Add nodes that fetch the inputs this routine needs (e.g. GitHub, Gmail / email, X / Twitter).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

Every day, scan support emails, reviews and X mentions for bug reports. De-duplicate, write clear repro steps and draft GitHub issues labeled by severity for my review.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
