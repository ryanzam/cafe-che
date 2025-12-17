# Cafe Che ☕ A web application for restaurant name Cafe Che

## Technologies used
[![Vite](https://img.shields.io/badge/Vite-Built%20with%20Vite-646CFF?style=flat&logo=vite)](https://vitejs.dev/)
[![React](https://img.shields.io/badge/React-18+-61DAFB?style=flat&logo=react)](https://react.dev/)
![tailwindcss](https://img.shields.io/badge/tailwindcss-%5E4.1.13-4F46E5?style=flat-square&logo=tailwindcss)
[![TypeScript](https://img.shields.io/badge/TypeScript-Strict%20Typing-3178C6?style=flat&logo=typescript)](https://www.typescriptlang.org/)
![lucide-react](https://img.shields.io/badge/lucide-react-%5E0.543.0-EF4444?style=flat-square&logo=lucide-react)
![sonner](https://img.shields.io/badge/sonner-%5E2.0.7-8B5CF6?style=flat-square&logo=sonner)

![Stars](https://img.shields.io/github/stars/ryanzam/cafe-che?style=social) ![Forks](https://img.shields.io/github/forks/ryanzam/cafe-che?style=social)

A modern React + TypeScript application built with Vite. Lightweight, fast, and configured with best practices—including Hot Module Replacement (HMR), type-safe ESLint rules, and support for both Babel and SWC-based React Fast Refresh.

Ideal as a starter template or boilerplate for new projects.

*(Last updated: September 2025 – Recent fixes for responsive card layouts on small devices)*

## Features

- 🚀 **Blazing-fast development** powered by Vite
- ⚛️ **React 18+** with Fast Refresh
- 🛡️ **TypeScript** for full type safety
- 🔍 **ESLint** with modern flat config and type-aware rules
- ⚡ Optional SWC support for even faster refresh
- 📱 Responsive design improvements (mobile-friendly cards)
- 🔥 Zero bloat — minimal, clean setup ready for extension

## Quick Start

### Prerequisites

- Node.js v18 or later
- npm, yarn, or pnpm

### Installation

```bash
git clone https://github.com/ryanzam/cafe-che.git
cd cafe-che
npm install

cafe-che/
├── public/                  # Static assets
├── src/                     # Source code
│   ├── assets/              # Images, icons, etc.
│   ├── components/          # Reusable components
│   ├── lib/ 
│   ├── pages/ 
│   ├── App.tsx
│   └── main.tsx
├── .gitignore
├── components.json          # Component metadata (e.g., for shadcn/ui)
├── eslint.config.js         # Modern ESLint flat config
├── index.html
├── package.json
├── tsconfig.json
├── tsconfig.app.json
├── tsconfig.node.json
└── vite.config.ts