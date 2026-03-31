# 🚀 FinSight – Financial Analytics Dashboard with Clerk, Prisma, PostgreSQL, Supabase, and Next.js

This repository hosts a modern, production-ready full-stack application built using:

- **Frontend**: React (via Next.js)
- **Authentication**: Clerk
- **Database ORM**: Prisma
- **Database**: PostgreSQL (hosted on Supabase)
- **Styling**: Tailwind CSS
- **Backend**: API routes via Next.js App Router
- **Deployment**: Ready for Vercel or similar platforms

---

## 📁 Project Structure

```plaintext
├── app/                # Next.js App Router with page and API routes
├── components/         # Reusable React components
├── data/               # Static or mock data
├── emails/             # Email templates or logic
├── hooks/              # Custom React hooks
├── lib/                # Utilities and helper functions
├── prisma/             # Prisma schema and migration files
├── public/             # Static files
├── .gitignore
├── README.md
├── middleware.js       # Middleware for auth or routing logic
├── next.config.mjs     # Next.js configuration
├── package.json
├── tailwind.config.mjs # Tailwind CSS config
└── tsconfig.json / jsconfig.json

---

🔐 Authentication
This project uses [**Clerk**](https://clerk.dev) for:
- User sign-in / sign-up
- Session management
- Social authentication support

🔑 Setup Clerk
1. Sign up at [Clerk.dev](https://clerk.dev)
2. Get your **frontend API** and **secret key**
3. Add them to your `.env` file:

```env
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

Made with ❤️ by Pranav Deshmukh
