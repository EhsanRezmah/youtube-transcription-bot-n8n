# YouTube Transcription Bot with Rate Limiting & Cost Management

> Telegram bot that automatically transcribes YouTube videos using **Apify** + **n8n** with smart validation, daily rate limiting per user, and AI-powered text processing.

## ✨ Features

- Automatic detection of YouTube links from Telegram messages
- Intelligent validation (correct link + daily usage limit per user)
- High-quality transcription using Apify
- AI Agent (OpenRouter) for text cleaning and smart chunking of long videos
- Complete logging of user activity in database
- Clean and user-friendly experience in Telegram

## 🛠 Tech Stack

- **n8n** — Main workflow engine
- **Apify** — YouTube transcription
- **OpenRouter + AI Agent** — Intelligent text analysis and cleaning
- JavaScript Code Nodes
- Telegram Bot API
- SQL Database — Rate limiting & logging

## 📸 Workflow Overview
<img width="1520" height="412" alt="image" src="https://github.com/user-attachments/assets/7d49dfb0-9c4e-4f12-9819-41b50a3c2462" />

## 🚀 How it Works

1. User sends a YouTube link via Telegram
2. Bot validates the link and checks daily usage limit per user
3. If valid → Apify extracts the transcription
4. **AI Agent** (powered by OpenRouter) analyzes, cleans and chunks the text
5. Clean result is sent back to the user
6. All activity is logged in database

## 🚀 Future Improvements

- Integrate **MCP (Model Context Protocol)** for more advanced agent capabilities
- Automatically save transcripts to a personal **RAG system**
- Multi-language support (currently best with English & German)
- Web dashboard for transcription history
- Voice message support (Telegram voice → transcription)
- Advanced cost monitoring and alerts

## 📌 Built with passion during Ausbildung in CCNET - Gießen
