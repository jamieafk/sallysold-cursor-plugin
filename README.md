# Sally Sold for Cursor

Invoices by [Sally Sold](https://sallysold.com), from your agent. Ask in plain words: "Bill Acme $1,200 for October design work" or "Same invoice as last month for Northwind".

## Setup

1. Install the plugin from the Cursor Marketplace.
2. The first time the agent uses Sally Sold, sign in and click **Allow**. No API key needed.
3. New account? The agent asks for your business name and invoice email, then makes your first invoice.

Disconnect any time from **Account → Connected apps** on sallysold.com.

## What the agent can do

| Tool | What it does |
|------|--------------|
| `get_account_context` | Your business details, clients, recent invoices and plan usage |
| `save_business_details` | Fill in a new account's business name and invoice email |
| `create_invoice` | Preview, then create an invoice |
| `duplicate_invoice` | Copy a previous invoice for the next billing period |
| `list_invoices` | Find invoices by client or status (paid, unpaid, overdue) |
| `get_invoice` | Read one invoice in full |
| `get_invoice_link` | A link to open the invoice, plus a short-lived PDF download link for you |
| `mark_invoice_paid` | Record a payment |

The agent is instructed to show you a preview and wait for your OK before it creates an invoice. PDF links are for you only: they expire after 24 hours or 5 downloads. Attach the PDF when you send it to your client.

## Pricing

Your first 6 invoices are free. After that, Sally Sold Pro is $9/month or $39/year, or stay on the free plan with 1 invoice a month. See [sallysold.com/pricing](https://sallysold.com/pricing).

## Support

[sallysold.com/faq](https://sallysold.com/faq) · [Privacy](https://sallysold.com/privacy) · [Terms](https://sallysold.com/terms)
