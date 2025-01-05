# Log Pose

<p align="center">
  An intelligent support chatbot built specifically for Crustdata's API documentation, powered by SvelteKit and AI capabilities.
</p>

<p align="center">
  🏆 Built for the Crustdata Build Challenge 2025
</p>

## Overview

Log Pose is a technical assistant designed to help developers understand and effectively use Crustdata's APIs. It provides real-time API validation, smart error correction, and seamless integration with support channels.

Try it out: [logpose.pages.dev](https://logpose.pages.dev)

## Features

### Level 0 - Basic Chat Interface

- Simple web interface for API documentation queries
- Natural language Q&A about Crustdata's APIs
- Clear, contextual responses with code examples

### Level 1 - Smart API Validation

- Real-time API call testing
- Automatic error detection and correction
- Format validation (e.g., region format standardization)
- Working code examples guaranteed

### Level 2 - Knowledge Base

- Integrated documentation updates
- Real Q&A from Crustdata support channels
- Comprehensive API knowledge base
- Dynamic learning from new support cases

### Level 3 - Slack Integration

- Seamless Slack channel monitoring
- Automated response drafting
- Role-based authorization
- Real-time support in Slack workspace

## Technical Stack

- SvelteKit frontend framework
- Vercel AI SDK for chat capabilities
- Edge runtime support
- Modern UI with shadcn/ui
- Vercel KV for chat history
- Auth.js for authentication

## Getting Started

1. Clone the repository
2. Install dependencies:

```bash
npm install
```

3. Set up environment variables (copy .env.example to .env)
4. Run the development server:

```bash
npm run dev
```

## Environment Variables

Ensure you have the following environment variables set:

- API keys for your AI model
- Authentication credentials
- Slack integration tokens (for Level 3)
- Database connection strings

## Deployment

The application is hosted on Cloudflare Pages at [logpose.pages.dev](https://logpose.pages.dev). You can also deploy your own instance to any SvelteKit-compatible hosting platform.

### Cloudflare Pages Deployment

1. Fork this repository
2. Connect your Cloudflare Pages account
3. Create a new project and select your forked repository
4. Configure your build settings:
   - Build command: `npm run build`
   - Build output directory: `build`
   - Node.js version: 18.x
5. Add your environment variables in the Cloudflare Pages dashboard
