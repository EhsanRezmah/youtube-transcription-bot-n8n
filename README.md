# YouTube Transcription Bot with Rate Limiting

Telegram bot that automatically transcribes YouTube videos using **Apify** and **n8n**.  
Includes intelligent validation, daily usage limits per user, text cleaning & chunking, and full logging.

## ✨ Features

- Automatic YouTube link detection from Telegram
- Smart validation (valid link + daily limit per user)
- High-quality transcription via Apify
- Text cleaning and smart chunking for long videos
- Logging user activity to database
- Clean and user-friendly Telegram interface

## 🛠 Tech Stack

- **n8n** (Workflow Automation)
- **Apify** — YouTube Transcription
- **OpenRouter** + **AI Agent** (for intelligent processing & decision making)
- JavaScript Code Nodes
- Telegram Bot API
- SQL Database (Rate limiting + Logging)

## 📸 Workflow Overview
<img width="1520" height="412" alt="image" src="https://github.com/user-attachments/assets/7d49dfb0-9c4e-4f12-9819-41b50a3c2462" />


## 🚀 How it Works

1. User sends a YouTube link in Telegram
2. Bot validates the link and checks daily usage limit
3. If valid → Apify extracts transcription
4. After transcription, an AI Agent powered by OpenRouter analyzes 
   and cleans the text before sending it to the user.
5. Result is sent back to user
6. All activity is logged

## 🚀 Future Improvements

- Integrate **MCP (Model Context Protocol)** to turn the bot into a more powerful AI Agent
- Save transcripts automatically into a **personal RAG system** (for future search & knowledge base)
- Add multi-language support (currently works best with English/German)
- Build a simple **Web Dashboard** to view transcription history
- Add voice message support (Telegram voice → transcription)
- Implement better cost monitoring and notifications when limit is near

## 📌 Built with passion during Ausbildung
