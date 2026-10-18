# Never miss a lead follow-up

The agent checks your CRM or inbox for leads that went quiet and drafts the next follow-up.

- **Agent:** Sales agent
- **Schedule:** Daily 11:00
- **Estimated time saved:** ~4 h/week (an estimate, not a measured result)
- **Works best with:** CRM (HubSpot, GHL…), Gmail / email
- **Fits:** Agency owner (marketing, web, AI), Consultant / coach / freelancer, Trades & home services, Real estate agent / team, Local business owner, Solo founder
- **Full page:** https://whatshouldmybotdo.com/use-cases/lead-follow-up-sequences

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Never miss a lead follow-up
Schedule: Daily 11:00
Tools I use: CRM (HubSpot, GHL…), Gmail / email.

Every day, find leads that haven't heard from me in 3+ days (CRM or email). For each, draft a short follow-up that references our last conversation and offers one clear next step. List them for approval, oldest first.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Never miss a lead follow-up
Run: Daily 11:00
Tools I use: CRM (HubSpot, GHL…), Gmail / email.

Instructions:
Every day, find leads that haven't heard from me in 3+ days (CRM or email). For each, draft a short follow-up that references our last conversation and offers one clear next step. List them for approval, oldest first.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Never miss a lead follow-up
Cadence: Daily 11:00
Tools I use: CRM (HubSpot, GHL…), Gmail / email.

You are my sales agent. Every day, find leads that haven't heard from me in 3+ days (CRM or email). For each, draft a short follow-up that references our last conversation and offers one clear next step. List them for approval, oldest first.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Never miss a lead follow-up
When: Daily 11:00
Tools I use: CRM (HubSpot, GHL…), Gmail / email.

1. Create a new workflow. Add a Schedule Trigger (daily).
2. Add nodes that fetch the inputs this routine needs (e.g. CRM (HubSpot, GHL…), Gmail / email).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

Every day, find leads that haven't heard from me in 3+ days (CRM or email). For each, draft a short follow-up that references our last conversation and offers one clear next step. List them for approval, oldest first.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
