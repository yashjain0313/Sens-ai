nit# AI Career Coach

A full-stack AI-powered career coaching application built by **Yash Jain**.

## 🚀 Features

- **AI-Powered Interview Prep** - Generate mock interview questions tailored to your industry
- **Smart Resume Builder** - Build ATS-optimized resumes with AI assistance
- **Industry Insights** - Get real-time salary data, trends, and market analysis
- **Performance Tracking** - Track your interview preparation progress
- **Cover Letter Generator** - Create compelling cover letters with AI

## 🛠️ Tech Stack

- **Frontend:** Next.js 15, React 19, TailwindCSS, ShadCN UI
- **Backend:** Next.js Server Actions, Prisma ORM
- **Database:** PostgreSQL (NeonDB)
- **Authentication:** Clerk
- **AI:** Google Gemini 2.0 Flash
- **Background Jobs:** Inngest
- **Validation:** Zod, React Hook Form
- **Charts:** Recharts
- **Deployment:** Vercel

## 📦 Installation

```bash
# Clone the repository
git clone <your-repo-url>

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
# Add your API keys to .env.local

# Run database migrations
npx prisma migrate deploy
npx prisma generate

# Start development server
npm run dev
```

## 🔑 Environment Variables

```env
# Database
DATABASE_URL="your_neon_db_url"

# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your_clerk_publishable_key"
CLERK_SECRET_KEY="your_clerk_secret_key"

# Google Gemini AI
GEMINI_API_KEY="your_gemini_api_key"
```

## 👨‍💻 Developer

**Yash Jain**

## 📄 License

MIT License - feel free to use this project for learning and personal projects.
