# 10x-cards

A web application for quickly creating and managing educational flashcards with AI assistance.

## Table of Contents
- [Project Description](#project-description)
- [Tech Stack](#tech-stack)
- [Getting Started Locally](#getting-started-locally)
- [Available Scripts](#available-scripts)
- [Project Scope](#project-scope)
- [Project Status](#project-status)
- [License](#license)

## Project Description

10x-cards enables users to create and manage educational flashcard sets using AI-powered suggestions. The application leverages large language models (via API) to automatically generate flashcards from provided text, making the creation process significantly faster and more efficient.

### Key Features:
- **AI-Generated Flashcards**: Paste text and receive AI-suggested flashcards
- **Manual Flashcard Creation**: Create and manage flashcards manually
- **Spaced Repetition Learning**: Built-in algorithm for effective studying
- **User Authentication**: Secure account management system
- **Personal Flashcard Library**: Store and organize your flashcards

## Tech Stack

### Frontend
- **Astro 5**: Fast, efficient pages with minimal JavaScript
- **React 19**: Interactive components
- **TypeScript 5**: Static typing and better IDE support
- **Tailwind 4**: Utility-first CSS framework
- **Shadcn/ui**: Accessible React component library

### Backend
- **Supabase**: 
  - PostgreSQL database
  - Authentication
  - Backend-as-a-Service SDK

### AI Integration
- **Openrouter.ai**: API access to various LLM models (OpenAI, Anthropic, Google, etc.)

### CI/CD & Hosting
- **GitHub Actions**: CI/CD pipelines
- **DigitalOcean**: Application hosting via Docker

## Getting Started Locally

### Prerequisites
- Node.js version 22.14.0 (use nvm for version management)
- Git

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/10x-cards.git
   cd 10x-cards
   ```

2. Install Node.js with the correct version
   ```bash
   nvm install
   # or if you already have the version installed
   nvm use
   ```

3. Install dependencies
   ```bash
   npm install
   ```

4. Start the development server
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:4321`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build the production-ready application
- `npm run preview` - Preview the built application
- `npm run astro` - Run Astro CLI commands
- `npm run lint` - Run ESLint to check for code issues
- `npm run lint:fix` - Fix linting issues automatically
- `npm run format` - Format code with Prettier

## Project Scope

### Included in MVP
- User authentication (registration, login)
- AI-generated flashcards from text
- Manual flashcard creation and editing
- Basic spaced repetition algorithm integration
- Personal flashcard management

### Not Included in MVP
- Advanced, custom spaced repetition algorithm
- Gamification elements
- Mobile applications (web-only for now)
- Document import (PDF, DOCX, etc.)
- Public API
- Flashcard sharing between users
- Advanced notification system
- Advanced keyword-based flashcard search

## Project Status

MVP development in progress.

Success metrics:
- 75% of AI-generated flashcards accepted by users
- At least 75% of new flashcards created using AI assistance
- Engagement measured by generated vs. approved flashcard ratio

## License

This project is licensed under the MIT License - see the LICENSE file for details.
