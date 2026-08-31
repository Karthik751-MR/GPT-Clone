# GPT-Clone

> A full-stack conversational AI interface inspired by modern chat assistants.

GPT-Clone provides a chat experience with conversation history, streamed AI responses, Markdown/code rendering, and configurable AI API integration.

## Features

- Streaming AI responses
- Multi-conversation history
- Markdown and syntax-highlighted code rendering
- Copyable code blocks
- Responsive chat interface
- AI provider integration

## Tech Stack

- React
- Node.js
- Express
- Tailwind CSS
- AI APIs (OpenAI/Gemini depending on configuration)

## Project Structure

```text
GPT-Clone/
├── chatgpt-clone/
│   ├── backend/        # API and AI integration
│   └── client/         # React frontend
├── .gitignore
└── README.md
```

## Getting Started

### Backend

```bash
cd chatgpt-clone/backend
npm install
```

Create the required `.env` configuration for your selected AI provider, then start the server:

```bash
npm start
```

### Frontend

```bash
cd ../client
npm install
npm run dev
```

## Security

Keep API keys in environment variables and never commit `.env` files or provider credentials.

## Author

**Karthik Raj M R** — [@Karthik751-MR](https://github.com/Karthik751-MR)