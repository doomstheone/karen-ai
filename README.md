# KAREN AI Website

A full multi-section AI workspace starter built with Next.js 14, React, TypeScript and Tailwind CSS.

## Run locally on Windows 11

1. Install Node.js LTS: https://nodejs.org/en/download
2. Extract this folder.
3. Open the folder in VS Code or Windows Terminal.
4. Run `npm install`.
5. Copy `.env.example` to `.env.local`.
6. Add your provider API key and model to `.env.local` (optional for preview; required for live AI responses).
7. Run `npm run dev`.
8. Open http://localhost:3000.

## Deploy to get a public website link

Deploy this Next.js project using https://vercel.com/new. Configure `AI_API_KEY`, `AI_BASE_URL`, and `AI_MODEL` as server-side environment variables in the hosting dashboard. Do not put secrets in client-side code or NEXT_PUBLIC variables.

## Honest feature status

The UI includes chat, research, coding, writing, image, learning, voice and settings sections. The chat endpoint supports an OpenAI-compatible chat-completions API when configured. The other workspaces are currently interface placeholders; they do not yet perform live web research, image generation, voice processing or document analysis. Authentication, persistent history, file handling, quotas, rate limits and production monitoring must be added before public production use.
