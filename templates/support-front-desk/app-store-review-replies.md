# Reply to every app review

The agent drafts thoughtful replies to app store reviews and turns complaints into a bug list.

- **Agent:** Support / front-desk agent
- **Schedule:** Daily 10:00
- **Estimated time saved:** ~2 h/week (an estimate, not a measured result)
- **Works best with:** GitHub
- **Fits:** Indie app developer / studio
- **Full page:** https://whatshouldmybotdo.com/use-cases/app-store-review-replies

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Reply to every app review
Schedule: Daily 10:00
Tools I use: GitHub.

Every day, pull new App Store / Play reviews. Draft a short personal reply for each. Group complaints into bugs and feature requests and add them to my GitHub issues as drafts for review.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Reply to every app review
Run: Daily 10:00
Tools I use: GitHub.

Instructions:
Every day, pull new App Store / Play reviews. Draft a short personal reply for each. Group complaints into bugs and feature requests and add them to my GitHub issues as drafts for review.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Reply to every app review
Cadence: Daily 10:00
Tools I use: GitHub.

You are my support / front-desk agent. Every day, pull new App Store / Play reviews. Draft a short personal reply for each. Group complaints into bugs and feature requests and add them to my GitHub issues as drafts for review.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Reply to every app review
When: Daily 10:00
Tools I use: GitHub.

1. Create a new workflow. Add a Schedule Trigger (daily).
2. Add nodes that fetch the inputs this routine needs (e.g. GitHub).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

Every day, pull new App Store / Play reviews. Draft a short personal reply for each. Group complaints into bugs and feature requests and add them to my GitHub issues as drafts for review.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
