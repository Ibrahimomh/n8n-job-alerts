Remote Job Alerts

Pulls remote jobs from RemoteOK, filters duplicates using Supabase, analyzes each with AI, and sends a Telegram notification.

Setup


1- Import the workflow JSON into n8n
2- Create a Supabase table called jobs with columns: remote_id (unique), title, company, url
3- Add your credentials: Supabase, Telegram bot, Groq API key
4- Activate the workflow
