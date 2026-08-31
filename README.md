# GPT-Clone 🤖

> **A full-stack conversational AI interface built for real conversations, code, and context.**

GPT-Clone is a modern chat application with a React frontend and Node/Express backend. It combines streaming AI responses, conversation history, Markdown/code rendering, and configurable AI provider integration into a familiar assistant-style experience.

<div align="center">

[![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)](https://expressjs.com/)
[![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)

</div>

## 🧠 What It Does

The application provides the core interaction patterns users expect from an AI assistant:

**ask → stream → render → continue the conversation**

It also treats generated code as a first-class output, with Markdown formatting and copyable code blocks.

## ✨ Features

- 💬 Conversational AI interface
- ⚡ Streaming AI responses
- 🗂️ Multiple conversation/history handling
- 📝 Markdown rendering
- 💻 Syntax-highlighted code output
- 📋 Copyable code blocks
- 📱 Responsive chat UI
- 🔌 Configurable AI API integration

## 🏗️ Architecture

```text
┌──────────────────┐
│   React Client   │
│ Chat + History   │
└────────┬─────────┘
         │ HTTP / Stream
         ▼
┌──────────────────┐
│ Express Backend  │
│ API + AI Adapter │
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│   AI Provider    │
│ OpenAI / Gemini  │
└──────────────────┘
```

## 🛠️ Tech Stack

| Layer | Technology |
| --- | --- |
| Frontend | React |
| Backend | Node.js + Express |
| Styling | Tailwind CSS |
| AI | Configurable AI APIs |
| Output | Markdown + code rendering |

## 📁 Project Structure

```text
GPT-Clone/
├── chatgpt-clone/
│   ├── backend/          # Express API + AI integration
│   └── client/           # React frontend
├── .gitignore
└── README.md
```

## 🚀 Getting Started

### Backend

```bash
cd chatgpt-clone/backend
npm install
npm start
```

Configure the required AI provider credentials in a local `.env` file.

### Frontend

```bash
cd ../client
npm install
npm run dev
```

Open the local development URL shown by Vite/the configured frontend server.

## 🔐 Security

AI provider keys must stay on the server. Never expose private API credentials in React client code or commit `.env` files.

## 🧪 Test Scenarios

- Empty prompt
- Long prompt
- Streaming interruption
- Provider/API failure
- Multiple conversations
- Code-heavy responses
- Markdown edge cases
- Invalid credentials
- Rapid repeated submissions

## 🗺️ Roadmap

- [ ] Authentication
- [ ] Persistent conversation storage
- [ ] Multiple model selection
- [ ] Regenerate/edit messages
- [ ] File attachments
- [ ] Token/cost visibility
- [ ] Rate limiting

## 👤 Author

**Karthik Raj M R** — [@Karthik751-MR](https://github.com/Karthik751-MR)