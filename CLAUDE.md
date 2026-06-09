# LeadCRM — Lead Platform

This is the standalone lead CRM platform at `/Users/tkmac/Desktop/LeadCRM/`.
It is a separate project from the Starter/website repo.

## Structure
**Frontend:** `public/crm.html`
**Backend routes:** `server/routes/finder.js`, `server/routes/outreach.js`
**Backend services:** `server/services/claude.js`, `server/services/gmail.js`
**Server entry:** `server/server.js`
**GitHub repo:** https://github.com/Leadvolver/leadvolver-crm

## AI Agents
- 🤖 **AI Lead Finder** — searches web for leads by city + industry (`/api/finder`)
- 📧 **Email Outreach** — AI cold emails + auto follow-up scheduler (`/api/outreach/email`)
- 💼 **LinkedIn Messages** — generates 300-char connection requests (`/api/outreach/linkedin`)

## Pushing changes
Always push from this folder: `git push origin main`
