# Cursor Rules for Modern React & Web3 Stack

This repository contains a comprehensive set of Cursor AI rules for building applications with a modern React and Web3 tech stack.

## What Are Cursor Rules?

Cursor rules are guidelines stored in the `.cursor/rules` directory that help the Cursor AI understand best practices, conventions, and standards for your codebase. These rules serve as a reference for both AI and human developers to maintain consistency and quality.

## Tech Stack Coverage

The rules cover best practices for a complete modern React and Web3 stack:

- **Core**: React + TypeScript
- **Framework**: Next.js (App Router)
- **Styling**: Tailwind CSS + shadcn/ui
- **State Management**: Zustand (client) + TanStack Query (server)
- **Data Handling**: TanStack Form, Zod, TanStack Table
- **Animation**: Framer Motion
- **Backend/Database**: Turso (distributed SQLite) + Drizzle ORM (type-safe SQL and migrations)
- **Blockchain**: Hardhat, VeChain SDK JS, VeChain Kit
- **Deployment**: Vercel
- **Testing**: Vitest, React Testing Library, Playwright
- **Package Manager**: pnpm

## Rule Categories & Files

The rules are organized into the following categories and files:

- **Core Principles**: [core.mdc](.cursor/rules/core.mdc) — Fundamental development patterns and architecture
- **Tech Stack Standards**: [tech-stack.mdc](.cursor/rules/tech-stack.mdc) — Required technologies and their integration
- **Naming Conventions**: [naming.mdc](.cursor/rules/naming.mdc) — Standardized naming for files, components, and functions
- **Project Structure**: [structure.mdc](.cursor/rules/structure.mdc) — Directory organization and file placement
- **Coding Standards**: [coding-standards.mdc](.cursor/rules/coding-standards.mdc) — Specific coding patterns and styles
- **Best Practices**: [best-practices.mdc](.cursor/rules/best-practices.mdc) — Development workflow and implementation patterns
- **TanStack Query**: [tanstack-query.mdc](.cursor/rules/tanstack-query.mdc) — Server state management with TanStack Query
- **TanStack Form**: [tanstack-form.mdc](.cursor/rules/tanstack-form.mdc) — Form state management and validation with TanStack Form
- **Tailwind CSS**: [tailwindcss.mdc](.cursor/rules/tailwindcss.mdc) — Styling with Tailwind CSS and best practices
- **Hardhat**: [hardhat.mdc](.cursor/rules/hardhat.mdc) — Smart contract development, testing, and scripting with Hardhat (EVM & VeChain integration)
- **VeChain SDK JS**: [vechain-sdk-js.mdc](.cursor/rules/vechain-sdk-js.mdc) — VeChain blockchain development patterns and best practices
- **VeChain Kit**: [vechain-kit.mdc](.cursor/rules/vechain-kit.mdc) — Integration and usage patterns for VeChain Kit

## How to Use

1. Clone this repository or copy the `.cursor/rules` directory to your project
2. The AI assistant in Cursor will automatically reference these rules when writing code
3. Use the rules as a guide for maintaining consistency in your projects

## Benefits

- Consistent code style across your team
- Faster onboarding for new developers
- Better AI assistance with context-aware suggestions
- Adherence to modern best practices
- Higher quality code with standardized patterns
