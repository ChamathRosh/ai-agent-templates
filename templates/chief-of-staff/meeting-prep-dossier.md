# Meeting prep dossier before every call

30 minutes before a call you get who they are, what they want, past emails and suggested questions.

- **Agent:** Chief of Staff / CEO agent
- **Schedule:** 30 min before each meeting
- **Estimated time saved:** ~2 h/week (an estimate, not a measured result)
- **Works best with:** Google Calendar, Gmail / email, LinkedIn
- **Fits:** Agency owner (marketing, web, AI), Consultant / coach / freelancer, Solo founder, Real estate agent / team, Local business owner
- **Full page:** https://whatshouldmybotdo.com/use-cases/meeting-prep-dossier

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Meeting prep dossier before every call
Schedule: 30 min before each meeting
Tools I use: Google Calendar, Gmail / email, LinkedIn.

Before each external meeting on my calendar, research the attendees and their company, find our past email threads, and send me a one-page brief: who they are, likely goals, past context, 3 smart questions and the outcome I should aim for.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Meeting prep dossier before every call
Run: 30 min before each meeting
Tools I use: Google Calendar, Gmail / email, LinkedIn.

Instructions:
Before each external meeting on my calendar, research the attendees and their company, find our past email threads, and send me a one-page brief: who they are, likely goals, past context, 3 smart questions and the outcome I should aim for.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Meeting prep dossier before every call
Cadence: 30 min before each meeting
Tools I use: Google Calendar, Gmail / email, LinkedIn.

You are my chief of staff / ceo agent. Before each external meeting on my calendar, research the attendees and their company, find our past email threads, and send me a one-page brief: who they are, likely goals, past context, 3 smart questions and the outcome I should aim for.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Meeting prep dossier before every call
When: 30 min before each meeting
Tools I use: Google Calendar, Gmail / email, LinkedIn.

1. Create a new workflow. Add a Schedule Trigger, or the app trigger for the event (e.g. new email, new form entry, webhook).
2. Add nodes that fetch the inputs this routine needs (e.g. Google Calendar, Gmail / email, LinkedIn).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

Before each external meeting on my calendar, research the attendees and their company, find our past email threads, and send me a one-page brief: who they are, likely goals, past context, 3 smart questions and the outcome I should aim for.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
