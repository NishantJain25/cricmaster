# 🏏 Cricket Scoring App – Monorepo

This monorepo contains a full-stack cricket scoring application with mobile, web, and backend support. Built with **React Native**, **Next.js**, **Express.js**, **Prisma**, and managed via **Turborepo** and **pnpm** workspaces.

## 📁 Project Structure

cricmaster/
├── apps/
│ ├── mobile/ # React Native app (Expo)
│ ├── web/ # React / Next.js web app (admin panel)
│ └── backend/ # Express API with Prisma
│
├── packages/
│ ├── core/ # Shared scoring logic
│ ├── types/ # Shared TypeScript types
│ ├── hooks/ # Shared React hooks
│ └── ui/ (optional) # Shared UI components
│
├── prisma/ # Prisma schema & migrations (optional root location)
├── turbo.json # Turborepo configuration
├── tsconfig.base.json # Shared TS config
└── package.json # Root workspace configuration
