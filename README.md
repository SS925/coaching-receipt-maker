# Coaching Receipt Maker

A simple receipt maker for freelance coaching — no business name needed.

**Open the app:** https://ss925.github.io/coaching-receipt-maker/

## What it does
- Enter your own name once, then make receipts for clients (sessions, rate, discount, payment method).
- Live preview, **Download PDF**, and **Copy as text** for WhatsApp/email.
- Amount in words for ₹ (Indian numbering: lakh, crore).
- **Past receipts**: open any old receipt to download it again, or "Repeat for client" for the next month.
- Monthly and all-time totals.
- Back up / restore all receipts as a JSON file.

## Saving receipts to GitHub (private)
Receipts are saved to a separate **private** repo (default `SS925/coaching-receipts-data`) as `receipts.json`, one commit per receipt. This public repo only holds the app — never your receipts.

One-time setup on each device:
1. Create a private repo `coaching-receipts-data` (tick "Add a README").
2. Create a fine-grained token at https://github.com/settings/personal-access-tokens/new
   - Repository access: **Only select repositories** → `coaching-receipts-data`
   - Repository permissions: **Contents → Read and write**
3. In the app, open **My details** → paste the token → **Connect & save**.

The token is kept only in that browser. Without a token, receipts are saved in the browser only.

Everything is in one file: `index.html`.
