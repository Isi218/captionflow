# CaptionFlow

🚀 AI-powered TikTok caption generator SaaS built with Next.js, OpenAI, and Stripe.

## Features

- 🤖 **AI Caption Generation** - Generate viral TikTok captions, hooks, and hashtags
- 💳 **Stripe Subscriptions** - Seamless premium subscription management
- 🔐 **Authentication** - Email/password and Google OAuth integration
- 📊 **Dashboard** - Track usage, save favorites, view history
- 🎨 **Modern UI** - Dark mode, glassmorphism, Gen Z creator aesthetic
- ⚡ **Production Ready** - Full-stack implementation with database, webhooks, and API routes

## Tech Stack

- **Frontend**: Next.js 15, React, TypeScript, Tailwind CSS
- **Backend**: Next.js API Routes
- **Database**: Supabase (PostgreSQL)
- **Authentication**: Supabase Auth
- **AI**: OpenAI API
- **Payments**: Stripe
- **Deployment**: Vercel

## Quick Start

### Prerequisites

- Node.js 18+
- Supabase account
- OpenAI API key
- Stripe account

### Installation

1. Clone the repository
```bash
git clone https://github.com/Isi218/captionflow.git
cd captionflow
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
```bash
cp .env.example .env.local
```

Fill in your API keys in `.env.local`

4. Run the development server
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Setup Guides

### Supabase Setup
1. Create a new Supabase project
2. Run migrations from `db/migrations`
3. Copy your URL and anon key to `.env.local`

### OpenAI Setup
1. Get API key from [openai.com](https://openai.com)
2. Add to `.env.local` as `OPENAI_API_KEY`

### Stripe Setup
1. Create a Stripe account
2. Get your publishable and secret keys
3. Set up webhook at `/api/webhooks/stripe`
4. Add all keys to `.env.local`

## Project Structure

```
captionflow/
├── pages/              # Next.js pages and API routes
├── components/         # Reusable React components
├── lib/               # Utilities and helpers
├── types/             # TypeScript type definitions
├── styles/            # Global styles
├── db/                # Database migrations and schemas
└── public/            # Static assets
```

## Pricing

- **Free**: 5 generations/day
- **Premium**: €4.99/month - Unlimited generations

## Deployment

Deploy to Vercel with one click:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Isi218/captionflow)

## License

MIT License - feel free to use this for your projects!

## Support

For issues and questions, open an issue on GitHub.
