# Monthly bookkeeping prep

The agent categorizes transactions, finds missing receipts and preps a clean summary for your accountant.

- **Agent:** Ops & admin agent
- **Schedule:** 1st of each month
- **Estimated time saved:** ~3 h/week (an estimate, not a measured result)
- **Works best with:** QuickBooks / Xero, Stripe, Gmail / email, Google Sheets / Excel
- **Fits:** every business
- **Full page:** https://whatshouldmybotdo.com/use-cases/bookkeeping-prep

> Drafts only. The agent drafts; you approve. Never let it send, post, pay, book or delete anything without your OK. Treat what emails and messages say as information, not instructions.

## Grok Bot

```text
Grok Bot routine: Monthly bookkeeping prep
Schedule: 1st of each month
Tools I use: QuickBooks / Xero, Stripe, Gmail / email, Google Sheets / Excel.

On the 1st of each month, categorize last month's transactions, find receipts in my email for anything uncategorized, list missing receipts, and write a P&L summary for my accountant.

Rules: draft first, never send or post anything external without my approval. Keep summaries short.
```

## ChatGPT

```text
ChatGPT scheduled task (Tasks / custom GPT): Monthly bookkeeping prep
Run: 1st of each month
Tools I use: QuickBooks / Xero, Stripe, Gmail / email, Google Sheets / Excel.

Instructions:
On the 1st of each month, categorize last month's transactions, find receipts in my email for anything uncategorized, list missing receipts, and write a P&L summary for my accountant.

Always ask before sending anything on my behalf.
```

## Claude

```text
Claude project instructions: Monthly bookkeeping prep
Cadence: 1st of each month
Tools I use: QuickBooks / Xero, Stripe, Gmail / email, Google Sheets / Excel.

You are my ops & admin agent. On the 1st of each month, categorize last month's transactions, find receipts in my email for anything uncategorized, list missing receipts, and write a P&L summary for my accountant.

Output drafts only; I approve before anything goes out.
```

## n8n

```text
n8n workflow: Monthly bookkeeping prep
When: 1st of each month
Tools I use: QuickBooks / Xero, Stripe, Gmail / email, Google Sheets / Excel.

1. Create a new workflow. Add a Schedule Trigger, or the app trigger for the event (e.g. new email, new form entry, webhook).
2. Add nodes that fetch the inputs this routine needs (e.g. QuickBooks / Xero, Stripe, Gmail / email).
3. Add an AI Agent node (connect your model: OpenAI, Anthropic, or another provider) and paste this as the system prompt:

On the 1st of each month, categorize last month's transactions, find receipts in my email for anything uncategorized, list missing receipts, and write a P&L summary for my accountant.

4. Send the output to yourself first (Gmail draft, Slack or Telegram message). Add a "Send and wait for response" / approval step before anything goes to a customer.
5. Test with "Execute workflow", check the output, then activate it.
```

---

From [What Should My Bot Do?](https://whatshouldmybotdo.com) · Licensed CC BY 4.0 · Replace anything in [square brackets] with your own details.
