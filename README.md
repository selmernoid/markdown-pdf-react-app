# Markdown Editor App

A React-based markdown editor with real-time preview and PDF export functionality.

## Features

- Split-screen markdown editor with syntax highlighting
- Real-time preview with scroll synchronization
- PDF export functionality
- File operations (save/load markdown files)
- Responsive design for mobile and desktop
- TypeScript support for type safety

## Tech Stack

- **React 18+** with TypeScript
- **Vite** for build tooling and development server
- **marked** for markdown parsing
- **highlight.js** for syntax highlighting
- **jsPDF** and **html2canvas** for PDF generation
- **Vitest** and **React Testing Library** for testing
- **ESLint** and **Prettier** for code quality

## Project Structure

```
src/
├── components/     # React components
├── services/       # Business logic and API services
├── types/          # TypeScript type definitions
├── hooks/          # Custom React hooks
├── context/        # React context providers
├── utils/          # Utility functions
└── test/           # Test setup and utilities
```

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Install dependencies:
   ```bash
   yarn install
   # or
   npm install
   ```

2. Start the development server:
   ```bash
   yarn dev
   # or
   npm run dev
   ```

3. Open [http://localhost:5173](http://localhost:5173) in your browser

## Available Scripts

- `yarn dev` - Start development server
- `yarn build` - Build for production
- `yarn preview` - Preview production build
- `yarn test` - Run tests
- `yarn test:watch` - Run tests in watch mode
- `yarn lint` - Run ESLint
- `yarn lint:fix` - Fix ESLint issues
- `yarn format` - Format code with Prettier
- `yarn format:check` - Check code formatting

## Development

This project follows the spec-driven development methodology. See the `.kiro/specs/markdown-editor-app/` directory for:

- `requirements.md` - Feature requirements and acceptance criteria
- `design.md` - Technical design and architecture
- `tasks.md` - Implementation plan and task list

## Testing

The project uses Vitest and React Testing Library for testing. Tests are located alongside source files with the `.test.tsx` extension.

Run tests:
```bash
yarn test
```

## Code Quality

The project uses ESLint and Prettier for code quality and formatting:

- ESLint configuration includes React, TypeScript, and Prettier rules
- Prettier is configured for consistent code formatting
- Pre-commit hooks ensure code quality standards

## License

This project is licensed under the MIT License.