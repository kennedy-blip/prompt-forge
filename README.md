# PromptForge

A dark, browser-first prompt engineering workbench for testing templates, composing multi-step prompt chains, and comparing model outputs. Built with React, TypeScript, Vite, and Tailwind CSS.

## Development

```bash
npm install
npm run dev
npm run build
```

## Deployment on Vercel

Import `kennedy-blip/prompt-forge`, use the Vite preset, set the build command to `npm run build`, and the output directory to `dist`.

## Model connectivity

The included playground uses a deterministic local simulation so the UI works immediately without exposing API keys. Connect real providers through a server-side API route or backend proxy before sending production prompts to hosted model APIs. Never put provider secrets in `VITE_*` variables.
