# Jason-AI

Your personal intelligent AI assistant.

## First build

This repository now includes a responsive single-page chat interface in `index.html`.

### Included
- Responsive dark, animated interface
- Chat UI with starter prompts
- Browser-local conversation history
- Speech output using the browser's speech synthesis
- Speech input where Web Speech Recognition is supported

### Important: AI backend not connected yet

The current demo uses simple placeholder responses. It is **not yet connected to a language model**. To enable real AI conversations, add a secure server-side API (for example, a serverless function) and store the provider API key as a deployment secret. Never put API keys in `index.html` or commit them to this public repository.

## Run locally

Open `index.html` in a modern browser, or serve the repository with any static web server.

## Publish with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. After deployment, the site will be available at:

   https://jayravey3-lang.github.io/Jason-AI/

GitHub Pages may take a few minutes to publish the first time.
