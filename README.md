# InkPress

A modern web application built with Next.js, TypeScript, and Tailwind CSS. This project features authentication, database integration, and a responsive UI built with Radix UI components.

## 🚀 Features

- **Modern Stack**: Built with Next.js 13+ and TypeScript
- **Authentication**: Secure user authentication with Clerk
- **Styling**: Beautiful UI with Tailwind CSS and Radix UI components
- **Database**: PostgreSQL database with Drizzle ORM
- **Form Handling**: React Hook Form with validation
- **Theming**: Dark/light mode support with next-themes
- **Notifications**: Toast notifications with Sonner

## 🛠️ Tech Stack

- **Framework**: [Next.js](https://nextjs.org/) 13+
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **UI Components**: [Radix UI](https://www.radix-ui.com/)
- **Authentication**: [Clerk](https://clerk.com/)
- **Database**: [Neon](https://neon.tech/) (Serverless Postgres)
- **ORM**: [Drizzle ORM](https://orm.drizzle.team/)
- **Icons**: [Lucide Icons](https://lucide.dev/)
- **Form Handling**: [React Hook Form](https://react-hook-form.com/)
- **Date Handling**: [date-fns](https://date-fns.org/)

## 🚀 Getting Started

### Prerequisites

- Node.js 18.0.0 or later
- pnpm (recommended) or npm/yarn
- A Clerk account for authentication
- A Neon database (or any PostgreSQL database)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/inkpress.git
   cd inkpress
   ```

2. Install dependencies
   ```bash
   pnpm install
   # or
   npm install
   # or
   yarn install
   ```

3. Set up environment variables
   - Copy `.env.example` to `.env.local`
   - Fill in the required environment variables

4. Run database migrations
   ```bash
   pnpm db:push
   # or
   npm run db:push
   ```

5. Start the development server
   ```bash
   pnpm dev
   # or
   npm run dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser

## 📦 Scripts

- `dev` - Start development server
- `build` - Build for production
- `start` - Start production server
- `lint` - Run ESLint
- `db:generate` - Generate database migrations
- `db:migrate` - Run database migrations
- `db:push` - Push schema to database
- `db:studio` - Open database studio

## 📂 Project Structure

```
.
├── app/                  # App Router
├── components/           # Reusable components
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions and configurations
├── public/               # Static files
├── styles/               # Global styles
├── .env.example          # Environment variables example
├── drizzle.config.ts     # Drizzle ORM configuration
├── next.config.js        # Next.js configuration
├── package.json          # Project dependencies
└── tsconfig.json         # TypeScript configuration
```

## 🙏 Acknowledgments

- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Radix UI Documentation](https://www.radix-ui.com/docs/primitives/overview/introduction)
- [Drizzle ORM Documentation](https://orm.drizzle.team/)
