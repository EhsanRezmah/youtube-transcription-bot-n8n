# YouTube Transcription Bot with Rate Limiting & Cost Management

> Intelligent Telegram bot that automatically transcribes YouTube videos using **Apify** + **n8n**, with smart rate limiting, validation, and AI-powered text processing.

## ✨ Features

- Automatic YouTube link detection from Telegram messages
- Smart validation (valid link + daily usage limit per user)
- High-quality transcription via Apify
- AI Agent powered by OpenRouter for text cleaning and smart chunking
- Full logging of user activity in database
- Clean and user-friendly Telegram interface

## 🛠 Tech Stack

- **n8n** — Main workflow automation engine
- **Apify** — YouTube transcription
- **OpenRouter + AI Agent** — Intelligent text analysis and cleaning
- JavaScript Code Nodes
- Telegram Bot API
- SQL Database — Rate limiting & logging

## 📸 Workflow Overview

<img width="1520" height="412" alt="image" src="https://github.com/user-attachments/assets/7d49dfb0-9c4e-4f12-9819-41b50a3c2462" />

## 🚀 How it Works

1. User sends a YouTube link in Telegram
2. Bot validates the link and checks daily usage limit per user
3. If valid → Apify extracts the transcription
4. **AI Agent** (powered by OpenRouter) analyzes, cleans and chunks the text
5. Clean result is sent back to the user
6. All activity is logged in database

## 🚀 Future Improvements

- Integrate **MCP (Model Context Protocol)** for advanced agent capabilities
- Automatically save transcripts into a personal **RAG system**
- Multi-language support (best with English & German)
- Web dashboard for transcription history
- Voice message support
- Advanced cost monitoring and alerts

## 📌 Built with passion during Ausbildung in Gießen
