# Wealth - AI-Powered Finance Management Platform

An **AI-powered financial management platform** that helps you track, analyze, and optimize your spending with **real-time insights**.



## ✨ Features
✔ **Advanced Analytics** – Get detailed insights into your spending patterns with AI-powered analytics  
✔ **Smart Receipt Scanner** – Extract data automatically from receipts using advanced AI technology  
✔ **Budget Planning** – Create and manage budgets with intelligent recommendations  
✔ **Multi-Account Support** – Manage multiple accounts and credit cards in one place  
✔ **Automated Insights** – Get automated financial insights and recommendations  

---

Framework: Next.js
UI & Styling: Tailwind CSS, ShadCN UI
Backend: Next.js API Routes
Database & ORM: Supabase, Prisma
Background Jobs & Workflows: Inngest
AI Integration: Google Gemini API
Authentication: Clerk Auth
Deployment: Vercel
]Version Control: Git & GitHub

---

## ⚙️ How It Works
1. **Create Your Account** – Simple and secure sign-up process
2. **Transaction-Goto transaction and add details of transaction or add reciept image ai will scan it**
3. **Dashboard page-Your transactions are saved in dashboard **
4. **Track Your Spending** – Automatically categorize and track transactions in real-time  
5. **Get Insights** – Receive AI-powered insights and recommendations to optimize your finances  


🌐 **Live Project**: [Add Your Live URL Here]  

---

## 📦 Installation

### 1. Clone the repository:
```bash
git clone https://github.com/harshthakur0106/ai-finance-platform.git
cd ai-finance-platform


.env setup

DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=

npm install
npx prisma generate
npx prisma migrate dev --name init
npx prisma db push
npm run dev


