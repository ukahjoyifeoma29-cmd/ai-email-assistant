# My AI Email Assistant Projects

Hey, I'm Joy. I started learning automation to help small businesses handle emails faster, so I built these 3 workflows with n8n, Zapier and OpenAI.

### 1. AI Email Assistant (n8n)
This one watches my Gmail. When a new email comes in:
- It uses AI to check if it's urgent, a client, or just spam
- Pulls out name, email and what the person wants
- Saves it to Google Sheet so I don't lose leads
- If it's urgent or from a client, it pings me on Slack and drafts a reply automatically

I built this because I was tired of missing important client emails.

### 2. Order Router (Zapier)
Simple one for shop orders.
- Google Form gets a new order
- Zapier checks the amount
- If it's high value, it goes to High Value sheet, if low, it goes to Low Value sheet
- Helps the owner know which orders to prioritize

### 3. AI Auto-Responder
- Gmail trigger -> AI writes a proper reply -> Sends reply
- Still testing this one, sometimes the AI reply is too formal so I'm tweaking the prompt

**What I used:** n8n, Zapier, OpenAI API, Gmail, Slack, Google Sheets. Mostly no-code but I added some JavaScript for the logic.

I'm still learning and improving them. Feedback is welcome!

- Joy (ukahjoyifeoma29-cmd)
