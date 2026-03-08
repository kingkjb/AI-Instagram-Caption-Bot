AI-Powered Instagram Caption Bot
​A self-hosted automation engine that transforms photo descriptions into viral-ready Instagram captions.

​🚀 Overview:
​This project uses n8n to orchestrate a workflow between Telegram and Google Gemini AI. Users send a message to a Telegram bot, which triggers a series of processing steps to return three high-quality captions.

​🛠️ Technical Architecture:
​Automation Engine: n8n (Self-hosted on Railway).
​LLM: Google Gemini 1.5 Flash.
​Backend Logic: Custom JavaScript node for character-limit management.
​Infrastructure: PostgreSQL (Database) & Redis (Cache).

​✨ Key Features:
​Viral Content Generation: Uses Gemini's vision-capable model to draft engaging copy and hashtags.
​Smart Message Chunking: Custom JS logic bypasses Telegram’s 4,096-character limit by splitting long AI responses into multiple messages.
​Production Ready: 24/7 background execution with persistent data logging.

![Workflow Diagram]
Screenshot 2026-03-08 205542.png

