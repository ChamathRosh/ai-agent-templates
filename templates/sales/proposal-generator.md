# Turn discovery calls into proposals

After a call, the agent turns notes or the transcript into a scoped proposal with pricing tiers.

- **Agent:** Sales agent
- **Schedule:** After each discovery call
- **Estimated time saved:** ~4 h/week (an estimate, not a measured result)
- **Works best with:** Notion, Gmail / email
- **Fits:** Agency owner (marketing, web, AI), Consultant / coach / freelancer
- **Full page:** https://whatshouldmybotdo.com/use-cases/proposal-generator

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Turn discovery calls into proposals
Schedule: After each discovery call
Tools I use: Notion, Gmail / email.

When I share call notes or a transcript, write a proposal: client's problem in their words, proposed solution, 3 pricing tiers (good/better/best), timeline, and next steps. Use my past proposals as the style guide.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Turn discovery calls into proposals
Run: After each discovery call
Tools I use: Notion, Gmail / email.

Instructions:
When I share call notes or a transcript, write a proposal: client's problem in their words, proposed solution, 3 pricing tiers (good/better/best), timeline, and next steps. Use my past proposals as the style guide.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Turn discovery calls into proposals
Cadence: After each discovery call
Tools I use: Notion, Gmail / email.

You are my sales agent. When I share call notes or a transcript, write a proposal: client's problem in their words, proposed solution, 3 pricing tiers (good/better/best), timeline, and next steps. Use my past proposals as the style guide.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Turn discovery calls into proposals
When: After each discovery call
Tools I use: Notion, Gmail / email.

1. Create a new workflow. Add a Schedule Trigger, or the app trigger for the event (e.g. new email, new form entry, webhook).
2. Add nodes that fetch the inputs this routine needs (e.g. Notion, Gmail / email).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

When I share call notes or a transcript, write a proposal: client's problem in their words, proposed solution, 3 pricing tiers (good/better/best), timeline, and next steps. Use my past proposals as the style guide.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
